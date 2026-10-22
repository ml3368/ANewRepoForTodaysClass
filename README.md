This is a repo that I've created for Section 4.2 of STA556 - Reproducibility and Replicability

To install quarto run the follow in your terminal:

wget https://github.com/quarto-dev/quarto-cli/releases/download/v1.10.19/quarto-1.10.19-linux-amd64.deb

then:

sudo apt-get install -y ./quarto-1.10.19-linux-amd64.deb

to check the installation run:

quarto --version

to produce a pdf you will also need to run:

quarto install tinytex

To preview the report in your browser, run this from the repository root:

quarto preview reports/final_report.qmd --host 0.0.0.0 --port 4444 --no-browser

The click open in browser. If this doesn't work, append /reports/final_report.html to the end of the URL, eg. https://humble-palm-tree-96pg4qgwwrv3x6vx-4444.app.github.dev/reports/final_report.html

(your URL will be similar but different)
