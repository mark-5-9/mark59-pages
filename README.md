
This is the <b>MARK59-PAGES</b> repository for Mark59 - it is specifically used to deploy versions of Mark59 Maven artifacts to the Mark59 Pages URL 
in the form of a Maven formatted repository.  Usage:   
<br>- Always deploy to main branch
<br>- Run the 'Publish Maven Artifacts to GitHub Pages' workflow (dropdown always set to main).  This will build and deploy the required artifacts
(automatically, on branch 'mvn-repo')
<br>- The Mark59 Pages will update, Page 'index.html' should display at 
<a href="https://mark-5-9.github.io/mark59-pages">https://mark-5-9.github.io/mark59-pages</a>
<br>- Artifacts in the repository can be referenced by including the Mark59 Pages repo as a repository in your Maven's project pom.xml:
<br>&nbsp;&nbsp;<pre>&lt;repositories&gt;&lt;repository&gt;&lt;id&gt;mark59-pages&lt;/id&gt;&lt;url&gt;https://mark-5-9.github.io/mark59-pages &lt;/url&gt;&lt;/repository&gt;&lt;/repositories&gt;</pre>
<br><br>

## Mark59 Website ..
<p>https://www.mark59.com
