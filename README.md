Download Link: https://assignmentchef.com/product/solved-cs3353-project-02-link-searching-and-community-discovery
<br>
5/5 - (1 vote)

<header></header>



 <main></main>



<span style="font-size: 2em;">Overview</span>

Assume you have a graph that represents some type of relationship between two people. For example, it could represent friendship in a social network like Facebook. Or it could represent co-authorship of a paper, article, or book. In these examples, we are considering the edges to be undirected. However, in social networks that have a “follow”-type relationship between two individuals, the edges would be directed. You’ll implement a set of algorithms related to searching the graph and community discovery.

Example network input:

<pre><code class="text language-text">[7]ABCDEFG[undirected]A - BA - CB - CB - DD - GD - FD - EG - FE - F</code></pre>

You’ll read in a control file that will contain a set of commands to be processed by your project.

<ul>

 <li><code>or</code> – Open a file for reading. Takes one argument – the file name.</li>

 <li>ex: <code>or g1.txt</code></li>

 <li><code>ow</code> – set the output file. Takes one argument – the name of the file.</li>

 <li>ex: <code>ow g1-output.txt</code></li>

 <li><code>dfs</code> – Depth first search. Takes one argument – the start node.</li>

 <li>ex: <code>dfs E</code></li>

 <li>Output: To come</li>

 <li><code>bfs</code> – Breadth first search. Takes one argument – the start node.</li>

 <li>ex: <code>bfs G</code></li>

 <li>Output: To come</li>

 <li><code>mc</code> – Make a Connection with the smallest number of introductions. Takes two arguments – the two people to attempt to connect.</li>

 <li>ex: <code>mc A D</code></li>

 <li>Output: A set of introductions that need to be made in order for person A to be introduced to person D.

  <ul>

   <li>Ex: <code>{(A - B), (B - D)}</code></li>

  </ul></li>

 <li><code>dc</code> – Discover Communities. No arguments. Implement the <a href="https://en.wikipedia.org/wiki/Girvan%E2%80%93Newman_algorithm" target="_blank" rel="noopener">Girvan-Newman algorithm</a> a set of reasonably well connected communities. You will define “reasonably”.</li>

 <li>Output: a set of communities, each community identified by its members presented in alphabetic order.</li>

 <li>Additional Resources on Girvan-Newman Algorithm:

  <ul>

   <li>Chapter 10 Section 2 of <a href="http://infolab.stanford.edu/~ullman/mmds/book0n.pdf" target="_blank" rel="noopener">Mining Massive Data Sets</a></li>

   <li><a href="http://snap.stanford.edu/class/cs224w-2010/slides/14-communities_annot.pdf" target="_blank" rel="noopener">Social and Information Network Analysis Course Slide Deck 14</a></li>

   <li>Girvan M. and Newman M. E. J., <a href="https://www.pnas.org/content/99/12/7821" target="_blank" rel="noopener">Community structure in social and biological networks</a>, Proc. Natl. Acad. Sci. USA 99, 7821–7826 (2002).</li>

  </ul></li>

</ul>