

        ````
       $ git clone https://github.com/emikuszewski/loves.git
       $ cd loves
       $ hugo --theme=material-design
       $ touch public/Staticfile
       $ cf push -n loves

Make sure you commit all your changes back to the git repo.

```bash
$ git add --all
$ git commit -am "New Content Added"
$ git push origin master
