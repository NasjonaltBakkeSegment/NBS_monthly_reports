# NBS_monthly_reports

This repository is meant to be as a server for the NBS monthly reports which are served through Github servers and Jupyter book.

To build the book including a page for previous reports, the yq application needs to be installed

`sudo snap install yq`

To create the PDF using LaTeX you must also do the following:

```
sudo apt-get install texlive-latex-extra \
                     texlive-fonts-extra \
                     texlive-xetex latexmk
```

To publish the HTML report to GitHub pages you need ghp-import

```
sudo apt install ghp-import
``````

The latest version of the report can be found here:
https://nasjonaltbakkesegment.github.io/NBS_monthly_reports
