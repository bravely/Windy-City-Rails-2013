# Seeing the Big Picture: Quick and Dirty Data Visualization with Ruby
by [Aja Hammerly (@thagomizer_rb)](http://www.twitter.com/thagomizer_rb)

github.com/thagomizer

http://www.thagomizer.com


## Data is Proof

## People Pattern Match.

## Pictures are Universal.

brew install graphviz
gem install graph


# DOT
* Simple language to describe graphs
* graphs are nodes and edges
* can edit attributes like colors and shapes

### Viewing DOT files
* GraphViz
* Tulip
* Just export, screw it

Nodes: What they sound like
Edges: Lines between nodes, making these imply nodes

`save [filename]`


```
digraph do
	/// errything hurr
end
```

www.colorbrewer2.com(www.graphviz.org/do/info/colors.html)

# Charts
### Highcharts

Include JQuery
Highcharts.js
**PAY ATTENTION TO HIGHCHARTS' LICENSE**

```
$(function () {
	$('#chart').highcharts({
	series: [}
	data: [10, 5, 3]
	}]
	)
)
```


# Data Extraction
Nokogiri
JSON: Just use Rails!
CSV: DO NOT USE A REGEX, you'll die
Regexes: Rubular woot woot