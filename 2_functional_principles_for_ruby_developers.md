# Functional Principles for Ruby Developers

by [**@jessitron**](http://www.twitter.com/jessitron) blog.jessitron.com

**Why** functional programming works. What we **don't** have to think about.

* If it's not testable, that's a codesmell.
* Data In -> Data Out(This allows full testing)
	* Don't access global state
	* modify input
	* change the world

(Roy Osharov?)

```
class Book

	def self.sum_prices(books)
		books.map(&:price).reduce(0, :+)
	end
```

~~~Problem easier, because we know each step of the way of data.~~~

#### USE FOR FUNCTIONAL PROGRAMMING

* ->(a) { lambda }
* function.call()


#### Errors are Data Too
* **Data is our product, software is a method of supply, not the product**
* `rubyz` gem?

#### Nil is Not Data
map_values :nil_noval

* Try not using nil, but instead using symbols, as they can supply some data


#### 5. Functional Composition
* Object Oriented: A owns B
* Functional: Fits together with
	* 
* Pipe operator in unix is awesome

#### 6. Be Lazy
Only carry the important data forward, don't hold everything in memory

* Laziness separates what to do from when to stop

Full code example
http://github.com/jessitron/fp4rd
