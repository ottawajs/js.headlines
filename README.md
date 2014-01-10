js.headlines
============

Repo for all the content of js.headlines() news segment for OttawaJS.

Please keep all presentations "self-contained" in their own directory, ie.
  * 2014/01-January/
  * 2014/02-February/
  * etc.

To serve presentations online, please do the following:
  * Edit the index.html file to include a link to your presentation:
    ```
     <a href="/2014/01-Feburary">February 2014 JS Headlines</a><br>
    ```
  * Merge your trunk changes into the gh-pages branch
    ```
    git branch gh-pages
    git merge origin master
    git push origin gh-pages
    ```
  * Visit http://ottawajs.github.io/js.headlines
