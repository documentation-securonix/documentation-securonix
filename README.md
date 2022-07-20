# Documentation

This repository contains the Documentation for Securonix products and services.

## To add new content:

For adding new content to the Documentation base, please follow the steps listed below:

1. If you are accessing the repo for the first time, clone the Root_Folder branch. If not, skip to step 2.
<pre><code> git clone -b Root_Folder --single-branch git@github.com:documentation-securonix/documentation-securonix.git
</code></pre>
2. If you already have a local repo, pull the recent changes. 
<pre><code> git pull origin Root_Folder
</code></pre>
3. Add a markdown file in the content/posts path in Root_Folder branch to add your data. Refer to the [markdown syntax]
4. Add necessary content in the markdown file
5. Add images/gifs etc in the static folder
6. Push your changes to the Root_Folder branch
<pre><code>git add .
git commit -m "Add commit message"
git remote add origin git@github.com:documentation-securonix/documentation-securonix.git
git push -u origin Root_Folder
</code></pre>
7. After a few minutes, the information you added would be automatically reflected in the Documentation website

[markdown syntax]: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
