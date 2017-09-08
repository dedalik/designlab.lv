---
ID: 1
post_title: Hello world!
author: dedalik
post_excerpt: ""
layout: post
permalink: https://designlab.lv/hello-world/
published: true
post_date: 2017-09-01 11:34:35
---
<h1>Welcome to StackEdit!</h1>

Hey! I'm your first Markdown document in <strong>StackEdit</strong><sup id="fnref-1-stackedit"><a href="#fn-1-stackedit">1</a></sup>. Don't delete me, I'm very helpful! I can be recovered anyway in the <strong>Utils</strong> tab of the <i class="icon-cog"></i> <strong>Settings</strong> dialog.

<hr />

<h2>Documents</h2>

StackEdit stores your documents in your browser, which means all your documents are automatically saved locally and are accessible <strong>offline!</strong>

<blockquote>
  <strong>Note:</strong>
  
  <ul>
  <li>StackEdit is accessible offline after the application has been loaded for the first time.</li>
  <li>Your local documents are not shared between different browsers or computers.</li>
  <li>Clearing your browser's data may <strong>delete all your local documents!</strong> Make sure your documents are synchronized with <strong>Google Drive</strong> or <strong>Dropbox</strong> (check out the <a href="#synchronization"><i class="icon-refresh"></i> Synchronization</a> section).</li>
  </ul>
</blockquote>

<h4><i class="icon-file"></i> Create a document</h4>

The document panel is accessible using the <i class="icon-folder-open"></i> button in the navigation bar. You can create a new document by clicking <i class="icon-file"></i> <strong>New document</strong> in the document panel.

<h4><i class="icon-folder-open"></i> Switch to another document</h4>

All your local documents are listed in the document panel. You can switch from one to another by clicking a document in the list or you can toggle documents using <kbd>Ctrl+[</kbd> and <kbd>Ctrl+]</kbd>.

<h4><i class="icon-pencil"></i> Rename a document</h4>

You can rename the current document by clicking the document title in the navigation bar.

<h4><i class="icon-trash"></i> Delete a document</h4>

You can delete the current document by clicking <i class="icon-trash"></i> <strong>Delete document</strong> in the document panel.

<h4><i class="icon-hdd"></i> Export a document</h4>

You can save the current document to a file by clicking <i class="icon-hdd"></i> <strong>Export to disk</strong> from the <i class="icon-provider-stackedit"></i> menu panel.

<blockquote>
  <strong>Tip:</strong> Check out the <a href="#publish-a-document"><i class="icon-upload"></i> Publish a document</a> section for a description of the different output formats.
</blockquote>

<hr />

<h2>Synchronization</h2>

StackEdit can be combined with <i class="icon-provider-gdrive"></i> <strong>Google Drive</strong> and <i class="icon-provider-dropbox"></i> <strong>Dropbox</strong> to have your documents saved in the <em>Cloud</em>. The synchronization mechanism takes care of uploading your modifications or downloading the latest version of your documents.

<blockquote>
  <strong>Note:</strong>
  
  <ul>
  <li>Full access to <strong>Google Drive</strong> or <strong>Dropbox</strong> is required to be able to import any document in StackEdit. Permission restrictions can be configured in the settings.</li>
  <li>Imported documents are downloaded in your browser and are not transmitted to a server.</li>
  <li>If you experience problems saving your documents on Google Drive, check and optionally disable browser extensions, such as Disconnect.</li>
  </ul>
</blockquote>

<h4><i class="icon-refresh"></i> Open a document</h4>

You can open a document from <i class="icon-provider-gdrive"></i> <strong>Google Drive</strong> or the <i class="icon-provider-dropbox"></i> <strong>Dropbox</strong> by opening the <i class="icon-refresh"></i> <strong>Synchronize</strong> sub-menu and by clicking <strong>Open from...</strong>. Once opened, any modification in your document will be automatically synchronized with the file in your <strong>Google Drive</strong> / <strong>Dropbox</strong> account.

<h4><i class="icon-refresh"></i> Save a document</h4>

You can save any document by opening the <i class="icon-refresh"></i> <strong>Synchronize</strong> sub-menu and by clicking <strong>Save on...</strong>. Even if your document is already synchronized with <strong>Google Drive</strong> or <strong>Dropbox</strong>, you can export it to a another location. StackEdit can synchronize one document with multiple locations and accounts.

<h4><i class="icon-refresh"></i> Synchronize a document</h4>

Once your document is linked to a <i class="icon-provider-gdrive"></i> <strong>Google Drive</strong> or a <i class="icon-provider-dropbox"></i> <strong>Dropbox</strong> file, StackEdit will periodically (every 3 minutes) synchronize it by downloading/uploading any modification. A merge will be performed if necessary and conflicts will be detected.

If you just have modified your document and you want to force the synchronization, click the <i class="icon-refresh"></i> button in the navigation bar.

<blockquote>
  <strong>Note:</strong> The <i class="icon-refresh"></i> button is disabled when you have no document to synchronize.
</blockquote>

<h4><i class="icon-refresh"></i> Manage document synchronization</h4>

Since one document can be synchronized with multiple locations, you can list and manage synchronized locations by clicking <i class="icon-refresh"></i> <strong>Manage synchronization</strong> in the <i class="icon-refresh"></i> <strong>Synchronize</strong> sub-menu. This will let you remove synchronization locations that are associated to your document.

<blockquote>
  <strong>Note:</strong> If you delete the file from <strong>Google Drive</strong> or from <strong>Dropbox</strong>, the document will no longer be synchronized with that location.
</blockquote>

<hr />

<h2>Publication</h2>

Once you are happy with your document, you can publish it on different websites directly from StackEdit. As for now, StackEdit can publish on <strong>Blogger</strong>, <strong>Dropbox</strong>, <strong>Gist</strong>, <strong>GitHub</strong>, <strong>Google Drive</strong>, <strong>Tumblr</strong>, <strong>WordPress</strong> and on any SSH server.

<h4><i class="icon-upload"></i> Publish a document</h4>

You can publish your document by opening the <i class="icon-upload"></i> <strong>Publish</strong> sub-menu and by choosing a website. In the dialog box, you can choose the publication format:

<ul>
<li>Markdown, to publish the Markdown text on a website that can interpret it (<strong>GitHub</strong> for instance),</li>
<li>HTML, to publish the document converted into HTML (on a blog for example),</li>
<li>Template, to have a full control of the output.</li>
</ul>

<blockquote>
  <strong>Note:</strong> The default template is a simple webpage wrapping your document in HTML format. You can customize it in the <strong>Advanced</strong> tab of the <i class="icon-cog"></i> <strong>Settings</strong> dialog.
</blockquote>

<h4><i class="icon-upload"></i> Update a publication</h4>

After publishing, StackEdit will keep your document linked to that publication which makes it easy for you to update it. Once you have modified your document and you want to update your publication, click on the <i class="icon-upload"></i> button in the navigation bar.

<blockquote>
  <strong>Note:</strong> The <i class="icon-upload"></i> button is disabled when your document has not been published yet.
</blockquote>

<h4><i class="icon-upload"></i> Manage document publication</h4>

Since one document can be published on multiple locations, you can list and manage publish locations by clicking <i class="icon-upload"></i> <strong>Manage publication</strong> in the <i class="icon-provider-stackedit"></i> menu panel. This will let you remove publication locations that are associated to your document.

<blockquote>
  <strong>Note:</strong> If the file has been removed from the website or the blog, the document will no longer be published on that location.
</blockquote>

<hr />

<h2>Markdown Extra</h2>

StackEdit supports <strong>Markdown Extra</strong>, which extends <strong>Markdown</strong> syntax with some nice features.

<blockquote>
  <strong>Tip:</strong> You can disable any <strong>Markdown Extra</strong> feature in the <strong>Extensions</strong> tab of the <i class="icon-cog"></i> <strong>Settings</strong> dialog.
  
  <strong>Note:</strong> You can find more information about <strong>Markdown</strong> syntax <a href="http://daringfireball.net/projects/markdown/syntax" title="Markdown">here</a> and <strong>Markdown Extra</strong> extension <a href="https://github.com/jmcmanus/pagedown-extra" title="Pagedown Extra">here</a>.
</blockquote>

<h3>Tables</h3>

<strong>Markdown Extra</strong> has a special syntax for tables:

<table>
<thead>
<tr>
  <th>Item</th>
  <th>Value</th>
</tr>
</thead>
<tbody>
<tr>
  <td>Computer</td>
  <td>$1600</td>
</tr>
<tr>
  <td>Phone</td>
  <td>$12</td>
</tr>
<tr>
  <td>Pipe</td>
  <td>$1</td>
</tr>
</tbody>
</table>

You can specify column alignment with one or two colons:

<table>
<thead>
<tr>
  <th align="left">Item</th>
  <th align="right">Value</th>
  <th align="center">Qty</th>
</tr>
</thead>
<tbody>
<tr>
  <td align="left">Computer</td>
  <td align="right">$1600</td>
  <td align="center">5</td>
</tr>
<tr>
  <td align="left">Phone</td>
  <td align="right">$12</td>
  <td align="center">12</td>
</tr>
<tr>
  <td align="left">Pipe</td>
  <td align="right">$1</td>
  <td align="center">234</td>
</tr>
</tbody>
</table>

<h3>Definition Lists</h3>

<strong>Markdown Extra</strong> has a special syntax for definition lists too:

<dl>
<dt>Term 1</dt>
<dt>Term 2</dt>
<dd>Definition A</dd>

<dd>Definition B</dd>

<dt>Term 3</dt>
<dd>
Definition C
</dd>

<dd>
Definition D

<blockquote>
  part of definition D
</blockquote>
</dd>
</dl>

<h3>Fenced code blocks</h3>

GitHub's fenced code blocks are also supported with <strong>Highlight.js</strong> syntax highlighting:

<pre><code>// Foo
var bar = 0;
</code></pre>

<blockquote>
  <strong>Tip:</strong> To use <strong>Prettify</strong> instead of <strong>Highlight.js</strong>, just configure the <strong>Markdown Extra</strong> extension in the <i class="icon-cog"></i> <strong>Settings</strong> dialog.
  
  <strong>Note:</strong> You can find more information:
  
  <ul>
  <li>about <strong>Prettify</strong> syntax highlighting <a href="https://code.google.com/p/google-code-prettify/">here</a>,</li>
  <li>about <strong>Highlight.js</strong> syntax highlighting <a href="http://highlightjs.org/">here</a>.</li>
  </ul>
</blockquote>

<h3>Footnotes</h3>

You can create footnotes like this<sup id="fnref-1-footnote"><a href="#fn-1-footnote">2</a></sup>.

<h3>SmartyPants</h3>

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

<table>
<thead>
<tr>
  <th></th>
  <th></th>
  <th>ASCII</th>
  <th>HTML</th>
</tr>
</thead>
<tbody>
<tr>
  <td></td>
  <td>Single backticks</td>
  <td><code>'Isn't this fun?'</code></td>
  <td>'Isn't this fun?'</td>
</tr>
<tr>
  <td></td>
  <td>Quotes</td>
  <td><code>"Isn't this fun?"</code></td>
  <td>"Isn't this fun?"</td>
</tr>
<tr>
  <td></td>
  <td>Dashes</td>
  <td><code>-- is en-dash, --- is em-dash</code></td>
  <td>-- is en-dash, --- is em-dash</td>
</tr>
</tbody>
</table>

<h3>Table of contents</h3>

You can insert a table of contents using the marker <code>[TOC]</code>:

[TOC]

<h3>MathJax</h3>

You can render <em>LaTeX</em> mathematical expressions using <strong>MathJax</strong>, as on <a href="http://math.stackexchange.com/">math.stackexchange.com</a>:

The <em>Gamma function</em> satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

<blockquote>
  <strong>Tip:</strong> To make sure mathematical expressions are rendered properly on your website, include <strong>MathJax</strong> into your template:
</blockquote>

<pre><code>&lt;script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"&gt;&lt;/script&gt;
</code></pre>

<blockquote>
  <strong>Note:</strong> You can find more information about <strong>LaTeX</strong> mathematical expressions <a href="http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference">here</a>.
</blockquote>

<h3>UML diagrams</h3>

You can also render sequence diagrams like this:

<pre><code class="sequence">Alice-&gt;Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob--&gt;Alice: I am good thanks!
</code></pre>

And flow charts like this:

<pre><code class="flow">st=&gt;start: Start
e=&gt;end
op=&gt;operation: My Operation
cond=&gt;condition: Yes or No?

st-&gt;op-&gt;cond
cond(yes)-&gt;e
cond(no)-&gt;op
</code></pre>

<blockquote>
  <strong>Note:</strong> You can find more information:
  
  <ul>
  <li>about <strong>Sequence diagrams</strong> syntax <a href="http://bramp.github.io/js-sequence-diagrams/">here</a>,</li>
  <li>about <strong>Flow charts</strong> syntax <a href="http://adrai.github.io/flowchart.js/">here</a>.</li>
  </ul>
</blockquote>

<h3>Support StackEdit</h3>

<a href="https://monetizejs.com/authorize?client_id=ESTHdCYOi18iLhhO&amp;summary=true"><img src="https://cdn.monetizejs.com/resources/button-32.png" alt="" /></a>

<div class="footnotes">
<hr />
<ol>

<li id="fn-1-stackedit">
<a href="https://stackedit.io/">StackEdit</a> is a full-featured, open-source Markdown editor based on PageDown, the Markdown library used by Stack Overflow and the other Stack Exchange sites.&#160;<a href="#fnref-1-stackedit">&#8617;</a>
</li>

<li id="fn-1-footnote">
Here is the <em>text</em> of the <strong>footnote</strong>.&#160;<a href="#fnref-1-footnote">&#8617;</a>
</li>

</ol>
</div>