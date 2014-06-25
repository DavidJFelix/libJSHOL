libJSHOL
========

JSHOL stands for Javascript HTML Object Language. JSHOL is a subset of JSON that acts as a
domain specific language for creating HTML5 documents using JSON obbjects.

##Why? Why would you do that?

I **hate** SGML, XML and HTML. Tag-based markup is a terrible plague on the world and should
be purged from all systems, especially XML. I hope that one day, JSHOL won't be used to
translate JSHOL JSON into HTML, but instead will be the way that pages are transmitted. Why?
We're already using template lanuages and building pages from (insert your language) objects and
functions to assemble snippets of HTML... why not just serialize the model into a specialized JSON
object and use variables to fill data?

#From a very pedantic perspective
Whitespace between tags in tag based markup languages is not ignorable, but everyone treats it like
it is so that their \*ML is readable. In JSHOL, all content is contained as a string, so whitespace
for readability is ignored. This helps prevent strange indentation when using preformatted tags and
the like. Using JSON arrays, strings can span multiple lines cleanly.

I have, in the past, written HTML and XML in a way such that no whitespace was outside of tags, but
most people agreed that this was an unreadable monstrosity upon their eyes. See the "literal HTML"
sample for an example.
