# resume
For the HR ladies.

Alter GitHub Actions script for this.
```bash
# install latex
sudo apt install texlive-full

# clone repository
mkdir ~/Repositories
cd Repositories
git clone https://github.com/gutibran/resume

# build latex pdf
pdflatex ./brandon_gutierrez_resume.tex

# move latex pdf to the static web directory to serve on the website
mv ./brandon_gutierrez_resume.pdf ~/gutibran.com/static/
```
