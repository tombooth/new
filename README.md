
A bash script to create new projects and files from a set of templates.

When creating a project it will run through files replacing the following tokens:
   - #projectname# : with the name provided when creating a new project
   - #author#      : \ 
   - #email#       : |- these values are set at the top of the new script *change them*
   - #website#     : /

You can also provide -g as an option which, will intialise the folder as a git repo and commit the filled in template.
