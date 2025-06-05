README - < UbuntuStartup project documentation.<br>
6/5/25.	wmk.
<h3>Modification History.</h3>
<pre><code>
6/5/25.    wmk.   original document.
</code></pre>
<h3 id="IX">Documentation Sections.</h3>
<pre><code><a href="#1.0">link</a> 1.0 Project Description - overall project description.
<a href="#2.0">link</a> 2.0 Dependencies - project dependencies.
<a href="#3.0">link</a> 3.0 Project Build - step-by-step build instructions.
<a href="#4.0">link</a> 4.0 Significant Notes - important stuff not documented elsewhere.
</code></pre>
<h3 id="1.0">1.0 Project Description.</h3>
The UbuntuStartup project is the repository for all startup files that need to
be executed when a non-persistent Ubuntu system is started (typically from a
flashdrive). These startup shells and files take a "bare bones" Ubuntu system
and modify it to access a persistent filebase, as well as installing critical
applications to make it a viable development system.

The persistent filebase for the Ubuntu system will be pointed to by environment
variables that are preset whenever a Terminal session is started within the
non-persistent system. These environment variables are as follows:
<pre><code>
WINUBUNTU_PATH = Windows filebase ubuntu path
WINGIT_PATH = Windows filebase GitHub path
gitpath = GitHub projects filebase (usually set to WINGIT_PATH)
</code></pre>
<a href="#IX">Index</a>
<h3 id="2.0">2.0 Dependencies.</h3>
<h3 id="3.0">3.0 Project Build.</h3>
<h3 id="4.0">4.0 Significant Notes.</h3>
