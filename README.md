# Description
doi2bib is a module of [bibcure](https://github.com/bibcure/bibcure)and [scihub2pdf](https://github.com/bibcure/scihub2pdf)
![](https://raw.githubusercontent.com/bibcure/logo/master/gifs/doi2bib.gif) 

# Install

1. Clone the repository.
1. For Windows user, run `python.exe .\setup.py build`, it will create new folder `build` in the repository folder.
1. Open `build` folder, then `scripts-3.8` folder. There will be `doi2bib` file ready to run.

# How to use

Given a DOI number, then do

```
$ python doi2bib 10.1038/s41524-017-0032-0 >> file.bib
```

You also can generate a bibtex from a txt file containing a list of DOIs

```
$ python doi2bib --input file_with_dois.txt --output refs.bib
```

# Disclaimer

Process above tested on Windows 10 with Python 3.8.