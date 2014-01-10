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
  * Commit all of your trunk changes
    ```
    git commit -a

    git push origin master
    ```
  * Merge your trunk changes into the gh-pages branch
    ```
    git checkout gh-pages

    git merge origin master

    git push origin gh-pages

    git checkout master

    ```
  * Visit http://ottawajs.github.io/js.headlines
