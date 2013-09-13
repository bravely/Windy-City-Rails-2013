# Hardware and Rails

## Hardware Communication
.to_s(16) for hex
.to_i(2) for binary to ints

###### Books
1. Working with Ruby Threads
2. Growing with Object-Oriented Software, Guided by Tests


## Asynchronous Code

#### Sharing Data

1. Don't do it.
2. …don't share data across threads.
3. ….don't share mutable data.
4. ….synchronize access to that data.
-- Working with Ruby Threads

"Objects can break encapsulation by sharing references to mutable objects…" --GOOSGPT


Each thread or mutex *idea* deserves an *object*.

##### Embrace asynchronous testing.

def eventually(seconds)

### Asynchrounous Code: RECAP
* **Don't share** mutable objects
* Make **abstractions** for threads and mutexes
* Embrace Asynchronous testing

## Testing
Gaslight Podcast?

Formatting of Messages

Don't forget to test both sides, and in between:
End to End tests. Test whole thing in a single go.


Unit Tests: **Design of your code**
Integration Tests: **Stuff we can't change**
End to End tests: **Stuff works. Really.**

### Testing: RECAP
* Testing is Automated **and** manual
* Only **end to end tests** provide **comfort** that stuff works
* Your software **doesn't work** if it doesn't work **with other things**.

## Total Recap
* Hardware communication is **EASY**
* **Embrace** asynchronous programming
* Use **end to end** tests