# Contributing

This repo is really meant to be maintained on contributions. The author does not really have that much time to keep, track, and maintain all of these due to personal reasons.

It could be a great opportunity for someone trying to contribute to open source and github and see for themselves in practice what the flow is.

Regardless if you're experienced or very new, please just take care of the following guidelines

> I ( Saif Ul Islam ) am not responsible if resources in some of the folders are missing. 
> I will upload what I have. Anything labelled as `???` or simply does not exist where it is supposed to be, is something I simply don't know or have.
> Please feel free to contribute if you do, however

## WARNING

Please do not upload or contribute mid papers / past papers. It would hurt the integrity of this repository.
Any such pull requests would be ***denied*** without notice, comment, or explanation.

# Format

## Single Teacher Per Course

For a single teacher in the course,

- .gitignore
- README.md
- Recorded Notes
  - README.md
- Slides

Where,

1. .gitignore - for your personal use
2. README.md - to contain MISC info
3. Recorded Notes - for notes taken by students
4. Recorded Notes > README.md - for the names of the students that contributed
5. Slides - pptx, pdfs and other resources shared by the teacher.

## Multiple Teachers Per Course

For multiple teachers,

- :foreach SEMESTER in SEMESTERS:
  - :foreach COURSE in COURSES:
    - :foreach TEACHER in TEACHERS:
      - Recorded Notes
        - README.md 
      - Slides
      - README.md
    - :BOOK:
    - :COURSE_OUTLINE:
    - .gitignore
  - README.md
 
Where,
 
1. `Recorded Notes` is a folder that contains student notes and collected links by students. It can be a .md, a .tex, or a .pdf file.  
  Please remember that ***.TXT files*** are strictly not allowed because of formatting and ROI reasons
  Want to understand how .tex works? Check out `pdflatex` command ( Linux ) and [Overleaf](overleaf.com) to practice and work with .tex files
  If you are going to use .md files, mention your name and the date you started that file on.
  If you are going to use .tex files, use \maketitle to update your name, date, and title
2. `Slides` contain the lectures and material uploaded by that TEACHER
3. `README.md` for each `SEMESER` is supposed to contain just the course names, the name of the teachers, and the name of the books. 
  Please attach links to free versions of the books if found
4. `README.md` for each `TEACHER` should contain MISC information, such as links to google meets, online drive links, further readings, etc
5. :BOOK: is the PDF of the books
6. :COURSE_OUTLINE: is the course outline
7. .gitignore - if you have some personal project files or something like that you would like to ignore
8. Recorded Notes > README.md contains the name of the student authors. Thank you for the notes!

# On the positive note

You can take this as an opportunity to understand issues and pull requests! Somewhere where you can try and get into the habit of, if you want to.

# When to make an issue?

When,

- Some files contain the wrong information. In that case, please make a pull request to fix it, else if you don't know either, make an issue
- You would like to modify the structure a bit
- You have some feedback
- You face some file restrictions
- Some other technical issues, if they are to arise.

# New to contributing?

If you want to make a substantial contribution, open an issue to ask before working on it. 
It’s helpful to watch the project for a while (on GitHub, you can click “Watch” to be notified of all conversations), and 
get to know community members, before doing work that might not get accepted.

Read further on this guide, ["How to Contribute to Open Source"](https://opensource.guide/how-to-contribute/#:~:text=If%20you%20want%20to%20make,that%20might%20not%20get%20accepted.).

# Forks

Please feel free to fork this if you want to do something similar for your university!