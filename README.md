# Project_Template
This is a template to illustrate the recommended project structure as the homework2 for the course `Introduction to reproducible research practices via browser-based replication`. 

The following two sections are the suggestions for `Folder Structure` and `Naming Convention`.

## Folder Structure

Folders inside folders should be constructed in a tree-like structure. For an experiment, the folder normally contains at least five sub-folders: `analyses`,`data`,`experimens`, `notes`,`writings`. If necessary, additional `code`, `posters`, `presentations`,etc, might be included as well. A `README.md` file is recommended in each top-level folder to describe what is in which files. For these sub-folders, they should be structured like a `sub-tree`, here is an example of a `sub-tree`:

```
analyses
		01_pilot
				01_data_preprocessing.R
				02_data_plotting.R
				03_summary.Rmd
		02_main
				01_data_preprocessing.R
				02_data_plotting.R
				03_regression_models.R
				04_visualize_models.R
				05_summary.Rmd
```

## Naming Convention

##### Principle: Make file names machine-readable and human-readable, be consistent.

#### Do:

- Use numbers (left pad with `0`) as a prefix to order files, like `01_preface.docx`.
- Including keywords, append meaningful description to the end like `03_analysis_plan.R` instead of `03.R` .
- Use hyphen `-` to mean "different words of the same chunk" and underscore `_` to seperate different chunks
- Dates should be kept in `YYYY-MM-DD` format, such as `2009-01-01_original-analysis.R`.

#### Don't:

- Don't use white space and special characters like `^.*?+|$`, try to avoid accents like `ñ`
- Don't have names only differ in uppercase or lowercase



#### Reference:

- [Video "On the why and how of tidy cooperation in experimental research (using git for version control)" by Michael Franke](https://vimeo.com/412835411?embedded=true&source=video_title&owner=109586811)

- [Slides "File naming conventions" by Danielle Navarro](https://slides.djnavarro.net/project-structure/#1)
