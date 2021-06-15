# course_template
A template repository for NumFOCUS Academy courses.

We are using GitHub Classroom as a way to collect materials from course developers. 
After creating an "assignment" with this template repository, the lead course instructor can be sent a link that will allow them to create a repository for their course, under the NF Academy org.
Having a common folder structure will help us when building courses in the online platform with the contents on GitHub.

## Instructions

Use the link from GitHub Classroom to create your repository based on this template. 
Add your content as Jupyter notebooks in the `notebooks` folder, and name them with a numeric prefix:

- `01_title_of_first_lesson.ipynb`
- `02_title_of_second_lesson.ipynb`

The typical course will be 4 or 5 notebooks, fully narrated (i.e., please include full prose explaining code and worked examples).
Use plenty of headings to organize the content, and split Markdown cells at each heading. 
If a section is longer than what you might read on a single scroll of a laptop display, split the cell (this will help us when building the online course from the notebooks).

Put any data sets used in the worked examples in the `data` folder and add a file index in the README.md file in that folder. 
(Include any credits for data that you sourced from others.)
Add in the `images` and `scripts` folder any images embedded in the Markdown cells of your notebooks and any scripts imported or ran within code cells, respectively.

Optionally, you can share your slides in the `slides` folder. We prefer text-based source, but you an also drop PDF files in there (please no binaries like .pptx).


### License
Please add an open-source license of your choosing to the materials. Our recommendation is: BSD-3 (or MIT) license for code, CC-BY license for text and media, CC0 for data.
