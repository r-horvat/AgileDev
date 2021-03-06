# Site Documentation

All documentation is within the code base and is written in MarkDown.

Markdown is a plain text formatting syntax designed so that it can be converted to HTML. There is no clearly defined Markdown standard but if you comply to the following syntax the generated pages should be formatted correctly.

<table>
<tr>
<th colspan="2">Paragraphs and Breaks</th>
</tr>
<tr>
<td>
<pre class="prettyprint">
Markdown accepts text on consecutive lines
as a hard-wrapped paragraph.

Put a blank Line in between to start a new graph.
</pre>
</td>
<td>
<p>
Markdown accepts text on consecutive lines
as a hard-wrapped paragraph.
</p><br/>
<p>
Put a blank Line in between to start a new graph.
</p>
</td>
</tr>

<tr>
<th colspan="2">Headings</th>
</tr>
<tr>
<td>
<pre class="prettyprint">
# Header 1
## Header 2
### Header 3
</pre>
</td>
<td>
Header 1
Header 2
Header 3
</td>
</tr>

<tr>
<th colspan="2">Blockquote</th>
</tr>
<tr>
<td>
<pre class="prettyprint">
&gt; Blockquote.
</pre>
</td>
<td>
<blockquote><p>Blockquote.</p></blockquote>
</td>
</tr>

<tr>
<th colspan="2">Lists</th>
</tr>
<tr>
<td>
<pre class="prettyprint">
Start ordered list with number.

6. Ordered
7. List
    8. Items

Unordered list

* Unordered
* List
    * Item
</pre>
</td>
<td>
<ol style="list-style-type: decimal">
  <li>Ordered</li>
  <li>List
  <ol style="list-style-type: decimal">
    <li>Items</li>
  </ol></li>
</ol><p>Unordered list</p>
<ul>
  <li>Unordered</li>
  <li>List
  <ul>
    <li>Item</li>
  </ul></li>
</ul>
</td>
</tr>

<tr>
<th colspan="2">Links</th>
</tr>
<tr>
<td>
<pre class="prettyprint">
An [inline link](http://www.google.com/ "optional title").

An [inline link to header page](#Site_Documentation) references header on current page.

A [reference link][id].

[id] defined elsewhere

[id]: &lt;http://www.google.com/&gt; (optional title)

Linked URL: &lt;http://www.google.com/&gt;

Mail to: &lt;address@example.com&gt;
</pre>
</td>
<td>
<p>An <a class="externalLink" href="http://www.google.com/" title="optional title">inline link</a>.</p>
<p>An <a href="#Site_Documentation">inline link to header page</a> references header on current page.</p>
<p>A <a class="externalLink" href="http://www.google.com/" title="optional title">reference link</a>.</p>
<p><a class="externalLink" href="http://www.google.com/" title="optional title">id</a> defined elsewhere</p>
<p>Linked URL: <a class="externalLink" href="http://www.google.com/">http://www.google.com/</a></p>
<p>Mail to: <a class="externalLink" href="mailto:address@example.com">address@example.com</a></p>
</td>
</tr>

<tr>
<th colspan="2">Images</th>
</tr>
<tr>
<td>
<pre class="prettyprint">
![Alternative title image](images/Uniknow-logo.jpg)
</pre>
</td>
<td>
<img src="images/UniKnow-logo.jpg" alt="Alternative title image" />
</td>
</tr>

<tr>
<th colspan="2">Code</th>
</tr>
<tr>
<td>
<pre class="prettyprint">
Inline `code` example.

Preformatted code block:

    &lt;strong&gt;Just indent 4 spaces.&lt;/strong&gt;

Double-backticks (`` ` ``) delimit literal backticks
</pre>
</td>
<td>
<p>Inline <tt>code</tt> example.</p>
<p>Preformatted code block:</p>
<div class="source">
<pre class="prettyprint">&lt;strong&gt;Just indent 4 spaces.&lt;/strong&gt;</pre>
</div>
<p>Double-backticks (<tt>`</tt>) delimit literal backticks</p>
</td>
</tr>

</table>