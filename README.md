## bootstrap 4.1 pagnation

You can use the [editor on GitHub](https://github.com/luckmoshy/luckmoshypagnation.js/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

<figure class="highlight"><pre><code class="language-html" data-lang="html"><span class="nt">&lt;b:comment&gt;</span>=== Homepage ===<span class="nt">&lt;/b:comment&gt;</span>
<span class="nt">&lt;b:if</span> <span class="na">cond=</span><span class="s">'data:view.isHomepage'</span><span class="nt">&gt;</span>
  <span class="c">&lt;!-- https://example.blogspot.com --&gt;</span>
<span class="nt">&lt;/b:if&gt;</span>

<span class="nt">&lt;b:comment&gt;</span>=== Item page ===<span class="nt">&lt;/b:comment&gt;</span>
<span class="nt">&lt;b:if</span> <span class="na">cond=</span><span class="s">'data:view.isPost'</span><span class="nt">&gt;</span>
  <span class="c">&lt;!-- https://example.blogspot.com/&lt;year&gt;/&lt;month&gt;/&lt;permalink&gt;.html --&gt;</span>
<span class="nt">&lt;/b:if&gt;</span>

<span class="nt">&lt;b:comment&gt;</span>=== Static page ===<span class="nt">&lt;/b:comment&gt;</span>
<span class="nt">&lt;b:if</span> <span class="na">cond=</span><span class="s">'data:view.isPage'</span><span class="nt">&gt;</span>
  <span class="c">&lt;!-- https://example.blogspot.com/p/&lt;permalink&gt;.html --&gt;</span>
<span class="nt">&lt;/b:if&gt;</span>

<span class="nt">&lt;b:comment&gt;</span>=== Search (label) page ===<span class="nt">&lt;/b:comment&gt;</span>
<span class="nt">&lt;b:if</span> <span class="na">cond=</span><span class="s">'data:view.search.label'</span><span class="nt">&gt;</span>
  <span class="c">&lt;!-- https://example.blogspot.com/search/label/&lt;name&gt; --&gt;</span>
<span class="nt">&lt;/b:if&gt;</span>

<span class="nt">&lt;b:comment&gt;</span>=== Search (query) page ===<span class="nt">&lt;/b:comment&gt;</span>
<span class="nt">&lt;b:if</span> <span class="na">cond=</span><span class="s">'data:view.search.query'</span><span class="nt">&gt;</span>
  <span class="c">&lt;!-- https://example.blogspot.com/search?q=&lt;query&gt; --&gt;</span>
<span class="nt">&lt;/b:if&gt;</span>

<span class="nt">&lt;b:comment&gt;</span>=== Search (default) page ===<span class="nt">&lt;/b:comment&gt;</span>
<span class="nt">&lt;b:if</span> <span class="na">cond=</span><span class="s">'data:view.search and !data:view.search.label and !data:view.search.query'</span><span class="nt">&gt;</span>
  <span class="c">&lt;!-- https://example.blogspot.com/search --&gt;</span>
<span class="nt">&lt;/b:if&gt;</span>

<span class="nt">&lt;b:comment&gt;</span>=== Archive page ===<span class="nt">&lt;/b:comment&gt;</span>
<span class="nt">&lt;b:if</span> <span class="na">cond=</span><span class="s">'data:view.isArchive'</span><span class="nt">&gt;</span>
  <span class="c">&lt;!-- 1. https://example.blogspot.com/&lt;year&gt; --&gt;</span>
  <span class="c">&lt;!-- 2. https://example.blogspot.com/&lt;year&gt;/&lt;month&gt; --&gt;</span>
  <span class="c">&lt;!-- 3. https://example.blogspot.com/&lt;year&gt;_&lt;month&gt;_&lt;day&gt;_archive.html --&gt;</span>
<span class="nt">&lt;/b:if&gt;</span>

<span class="nt">&lt;b:comment&gt;</span>=== Error page ===<span class="nt">&lt;/b:comment&gt;</span>
<span class="nt">&lt;b:if</span> <span class="na">cond=</span><span class="s">'data:view.isError'</span><span class="nt">&gt;</span>
  <span class="c">&lt;!-- https://example.blogspot.com/404 --&gt;</span>
<span class="nt">&lt;/b:if&gt;</span>

<span class="nt">&lt;b:comment&gt;</span>=== Preview page ===<span class="nt">&lt;/b:comment&gt;</span>
<span class="nt">&lt;b:if</span> <span class="na">cond=</span><span class="s">'data:view.isPreview'</span><span class="nt">&gt;</span>
  <span class="c">&lt;!-- Preview page --&gt;</span>
<span class="nt">&lt;/b:if&gt;</span>

<span class="nt">&lt;b:comment&gt;</span>=== Layout mode ===<span class="nt">&lt;/b:comment&gt;</span>
<span class="nt">&lt;b:if</span> <span class="na">cond=</span><span class="s">'data:view.isLayoutMode'</span><span class="nt">&gt;</span>
  <span class="c">&lt;!-- https://www.blogger.com/blogger.g?blogID=&lt;blogID&gt;#pageelements --&gt;</span>
<span class="nt">&lt;/b:if&gt;</span></code></pre></figure>


For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### 

<div class="col-md-6 order-md-1 text-center text-md-left pr-md-5">
        <h1 class="mb-3 bd-text-purple-bright">Bootstrap</h1>
        <p class="lead">
Luckmoshy jQuery pagnation plugin  provide simple yet fully customisable pagination. </p>
        <p class="lead mb-4">
 <span class="s f-bold">Luckmoshy Jquery Pagination</span> is built completely with  Jquery elements so screen readers can announce the number of available links. Use a wrapping 
 element to identify it as a navigation section to screen readers and other assistive technologies.        </p>
        <div class="row mx-n2">
         <nav aria-label="Page navigation example mt-5">
 <ul id="luckmoshy" class="pagination pagination ">
   <!--luckmoshypagnation page are paging here-->
   </ul>
        </nav></div>
		<div class="row mx-n2 mt-5 mb-5 py-5">
          <div class="col-md px-2">
            <a href="pagnation.html" class="btn btn-lg btn-secondary w-100 mb-3" onclick="ga('send', 'event', 'Jumbotron actions', 'Get started', 'Get started');">Documetation</a>
          </div>
          <div class="col-md px-2">
            <a href="/docs/4.3/getting-started/download/" class="btn btn-lg btn-outline-secondary w-100 mb-3" onclick="ga('send', 'event', 'Jumbotron actions', 'Download', 'Download 4.3.1');">Download</a>
          </div>
        </div>
        <p class="text-muted mb-0">
          Currently v4.3.1
        </p>
      </div>

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
