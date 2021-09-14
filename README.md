# Education
This git is used to provide the content for the lectures. You will find materials such as exercise data, source code templates in Python and the LaTeX template here.  

## Recommendation for Standard Folder Structure in Your own Git: 
Folder:
```python
| - code 
  |- main.py
  |- Class.py
| - figures 
| - data 
| - docu
  | - LaTeX
  | - readme.md
```


# Git Commands in Terminal
```python
# Clone repo
git clone [url]

# Add. all local data for push commit
git add .

# Git pull to get the current stage of repo
git pull

# Prepare a messages for the commit command 
git commit -m "Text for the Team"

# Upload all data to the repo. 
git push
```

# Thesis:
You will find here a tamplate for a LaTeX document.
I provide here a few useful code lines for the LaTex document. 
The docuement folder is structured as follow: 
```python
| - chapter # All chapters
| - figure # All Figures it is useful to use vector formats like .pdf for high quality
|
main.tex # Built the complete project
preamble.sty # My style file for nice format
references.bib # The database for all references


```
