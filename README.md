# docs-companion

**Short description**: Gather latex templates for reports, course summaries, and cheatsheets. Overleaf bridge.

## Motivation 

After accumulating few projects in [Overleaf](https://www.overleaf.com/) (cloud-based LaTeX editor), I felt the need to centralize and backup documents / templates. Creating this repository, a [bridge](https://www.overleaf.com/learn/how-to/Using_Git_and_GitHub) between Overleaf and Github, provides an Overleaf entry point to easily perform a few tests and create new projects based on existing ones, while enjoying the version control of git.

## Example templates

#### Cheatsheets

<img src="res/signals-systems-example.jpg" width="300" />&nbsp;&nbsp;&nbsp;&nbsp;<img src="res/artificial-intelligence-example.jpg" width="300" />

#### Summaries

<img src="res/computer-security-example.jpg" width="300" />

## Project structure


### Bridge principles

* 1 GitHub repo linked with 1 Overleaf project
* Default view: README.md (GitHub) and main.tex (Overleaf)

#### Add templates to this repo

From Overleaf perspective, it is currently not possible to 
include all files of an external project (only a single file at a time can 
be uploaded). Best solution I found so far: download `.zip` files of 
projects from Overleaf, and unzip them in corresponding category.


### File structure

* Directory tree level 1 (i.e. root) : 
  * Name of template categories (e.g. cheatsheets)
  * Git README.md
  * main.tex
* Directory tree level 2  : 
  * specific example projects / templates 

#### Treeview of template structure

```
.
├── cheatsheets
│   ├── proj-cheatsheet-1
│   │   ├── foo.tex
│   │   ├── main.tex
│   │   ├── README.txt
│   ├── proj-cheatsheet-2
│   │   ├── main.tex
│   │   └── ...
│   └── ...
├── main.tex
├── overleaf-original
│   ├── project-1.zip
│   └── ...
└── summaries
    └── topic1
        └── ...
```

## To-have-on-hand commands 

### Generate PDF vignette for example projects READMEs

* PDF to SVG:
  ```bash
  $ inkscape --without-gui --file=input.pdf --export-plain-svg=output.svg
  ```




<!-- Add HTML break lines to improve markdown real-time visualization in PyCharm  -->
<br /><br /><br /><br /><br /> 
