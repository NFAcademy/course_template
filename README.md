# course_template
A template repository for NumFOCUS Academy courses.

We are using GitHub Classroom as a way to collect materials from course developers. 
After creating an "assignment" with this template repository, the lead course instructor can be sent a link that will allow them to create a repository for their course, under the NF Academy org.
Having a common folder structure will help us when building courses in the online platform with the contents on GitHub.

> Delete this file (or rename it) and replace it by a README file that targets the contents of the repository, populated with your course materials.

## Instructions

Use the link from GitHub Classroom to create your repository based on this template. 
Add your content as Jupyter notebooks in the `notebooks` folder, and name them with a numeric prefix:

- `01_title_of_first_lesson.ipynb`
- `02_title_of_second_lesson.ipynb`

The typical course will be 4 or 5 notebooks, fully narrated (i.e., please include full prose explaining all code and worked examples).
Use plenty of headings to organize the content, and split Markdown cells at each heading. 
If a section is longer than what you might read on a single scroll of a laptop display, split the cell (this will help us when building the online course from the notebooks).

Put any data sets used in the worked examples in the `data` folder and add a file index in the README.md file in that folder. 
(Include any credits for data that you sourced from others.)
Add in the `images` and `scripts` folders any images embedded in the Markdown cells of your notebooks and any scripts imported or ran within code cells, respectively.

Optionally, you can share any slides in the `slides` folder. We prefer text-based source, but you can also drop PDF files in there (please no binaries like .pptx).

**Important**: Add all code dependencies to the `requirements.txt` file. 

## How we build your course

The NumFOCUS Academy uses an instance of the [Open edX](https://open.edx.org/) software platform for online learning. 
We will build a course learning sequence by pulling content directly from your Jupyter notebooks, which will be displayed as embedded HTML in the course. 
Sections of a notebook can be displayed in the online course as a "unit" of the learning sequence, interleaved with videos or student assignments (graded or ungraded). 

Open edX allows a variety of [problem types](https://edx.readthedocs.io/projects/edx-partner-course-staff/en/latest/exercises_tools/create_exercises_and_tools.html), such as multiple choice, dropdown choice, numerical input, and even [math expression input](https://edx.readthedocs.io/projects/edx-partner-course-staff/en/latest/exercises_tools/math_expression_input.html#math-expression-input) problems.
We also have a third-party extension for graded assignments using Jupyter notebooks and [nbgrader](https://nbgrader.readthedocs.io/en/stable/).

### License
The source materials for NumFOCUS Academy courses are copyright of their authors. 
We ask that materials be shared under an open-source license of the author's choosing. Our recommendation is: BSD-3 (or MIT) license for code, CC-BY license for text and media, CC0 for data.


# General information

## What is NumFOCUS?

[NumFOCUS](http://numfocus.org) is a 501(c)-3 non-profit in the United States. Its mission is to promote open practices in research, data, and scientific computing by serving as a fiscal sponsor for open source projects and organizing community-driven educational programs. NumFOCUS envisions an inclusive scientific and research community that utilizes actively supported open source software to make impactful discoveries for a better world.

## NumFOCUS Academy

The NumFOCUS Academy is an educational initiative begun in 2020, 