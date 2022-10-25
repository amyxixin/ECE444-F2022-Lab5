# Amy Xin and Peter Wang
This repo is a clone of [https://github.com/nelaturuk/education_pathways](https://github.com/nelaturuk/education_pathways).

## Activity 1
<img width="1256" alt="Screen Shot 2022-10-25 at 6 14 09 PM" src="https://user-images.githubusercontent.com/22310955/197892282-978ca698-17f3-4c35-a17d-ea6ad7658128.png">
<img width="1348" alt="Screen Shot 2022-10-25 at 6 15 48 PM" src="https://user-images.githubusercontent.com/22310955/197892399-226bb6c8-e907-4c7b-a519-2c2d0eede391.png">


# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
