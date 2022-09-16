# This repo has files that are necessary to build a GitHub page using bookdown.
Finished website looks like this: https://riesadohara.github.io/bookdown_CrumpLab/index.html

# To use this as a template, 
0. First, install necessary R packages.
install.packages(“tinytex”) 
--> 
tinytex::install_tinytext() 
--> 
install.packages(“downlit”)

1. Download this whole repo as a Zip file.
2. Clone it as a repo in your GitHub.
3. Open bookdown-demo.Rproj (should open in RStuido)
4. From the Files tab (bottom right) of R Studio, Open _bookdown.yml
5. Build tab --> Build Book.
6. "docs" folder should have been created in your locally cloned repo.
7. Go to Settings on your repo page on the GitHub site.
8. From navigation pane on the left, select Pages.
9. Deploy from branch --> select "master(main)/docs" --> then Save.
10. Wait until it says "Your site is live at https://USERNAME.github.io/YREPO_NAME/"
11. When you open your page, it should have website that shows docs/index.html.
12. If not, try pushing local changes to the remote GitHub repo via GitHub Desktop.

NOTE: But this website do not have horizontal tabs... So, you need to either copy a repo from elsewhere that has the tab structure.  

# Resources
**bookdown** (https://github.com/rstudio/bookdown)

[Get Started](https://bookdown.org/yihui/bookdown/get-started.html) at https://bookdown.org/yihui/bookdown/

[Build the book](https://bookdown.org/yihui/bookdown/build-the-book.html)

The preview of this example at https://bookdown.org/yihui/bookdown-demo/
