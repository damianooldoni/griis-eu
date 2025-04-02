# griis-eu

Workflow to create an EUropean GRIIS checklist based on national GRIIS checklists. Inspired by [`trias-project/unified-checklist`](https://github.com/trias-project/unified-checklist).

## Repository structure

The repository structure is based on [Cookiecutter Data Science](http://drivendata.github.io/cookiecutter-data-science/). Files indicated with GENERATED should not be edited manually. This list can be not complete as the content of this repository is still in progress.

```
├── README.md              : Description of this repository
├── LICENSE                : Repository license
├── griis-eu.Rproj         : RStudio project file
├── .gitignore             : Files and directories to be ignored by git
│
├── data
│   ├── raw
│   │   ├── checklists.csv
│   │   └── distributions.csv
│   ├── interim
|       ├── taxa_unified.csv
│   │   └── distributions_unified.csv
│   └── output
└── src
│   └── griis_europe.qmd  : Script to generate an European GRIIS checklist based on national GRIIS checklistsµ
└── docs: GENERATED Folder with website
```
