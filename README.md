# JustinBrantley_CV

This is the Latex file for my personal CV/resume. It is basically a Frankenstein version of the [Alta CV](https://github.com/liantze/AltaCV) template with some substantial changes that added new section types and slightly different formatting. Unfortunately, I added this project to github after I had done the majority of the major surgical operations so that versioning history is lost. I tried to annotate most of the changes in the .cls file with a `% JB Edit` comment. 

Some important things to note:

- The `main.tex` file is the main file,... as you might have guessed.
- The individual sections within the CV are in individual `.tex` files in the `/sections` folder. I did it this way so that I can easily change the order or content of the CV.
- There is a boolean, `\newif\iftwopage`, that allows me to toggle between a two page resume and a full CV be setting  `\twopagetrue` or `\twopagefalse`. 

I've included a copy of my 2-page resume/CV and full CV for reference.  
