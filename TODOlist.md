#  Todolist

## Dirk Eddelbuettel

- [ ] move to books to end, consider shortening the section and putting this into a complementary blog post etc, 
- [ ] make a link to the Finance TV strikes me as appropriate 
- [ ] nixing (removing) anchors 
- [ ] add some words on mortality data for people who are not aware of the good job done by HMD and other national statistics offices. 
- [ ] don't wrap lines


## Achim Zeileis

- [ ] An introduction is missing. This should set the scene, discuss inclusion/exclusion criteria (see above), etc. You can also include the acknowledgments in this intro.
- [ ] You use hard links to other task views. Please avoid that and use the dedicated `r view("...")` tags instead.
- [ ] Add a `### Links` section at the end of the .md. You do mention several relevant links in the text (e.g., mortality.org) and listing the important ones in a dedicated section at the end would be useful, I think.
- [ ] remove archived packages, https://github.com/cran-task-views/ctv/blob/main/Maintenance.md#CRAN-package-archivals
- [ ] If you want to hyperlink DOIs, you can easily do so with the `r doi("...")` tag. 
- [ ] You use `> ` quotes for the text that refers to other task views. I don't think this is really necessary. I would put this in regular text.
- [ ] the "Mortality databases" section is hard to parse if you miss the package description of `MortalityLaws` in the previous section. I would recommend putting the links into the dedicated `### Links` section at the end of the task view and mention this in the description of the `MortalityLaws` package. 