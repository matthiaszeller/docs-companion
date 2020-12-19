# docs-companion

**Short description**: Gather latex templates for reports, course summaries, and cheatsheets. Overleaf bridge.

## Motivation 

[Overleaf website](https://www.overleaf.com/) (cloud-based LaTeX editor) recently added a feature to classify projects by named and colored categories.
Until now, overleaf projects accumulated without well-defined structure. This new feature gave me the idea to create an 
overleaf-github bridge, in order to **centralize and backup** latex templates. 

## Project structure

### Description

* Directory tree level 1 (i.e. root) : 
  * Name of template categories (e.g. cheatsheets)
  * Git README.md
  * main.tex
* Directory tree level 2  : 
  * specific example projects / templates 

### Treeview of template structure

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
