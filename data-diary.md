# Data Diaries

https://ireapps.github.io/nicar-2020-schedule/#20200307_dear_diary_best_practices_for_keeping_a_data_diary_2105_all

What:
- Recipe for how to complete your analysis
- recording of every step you take, every decision you make
- reasoning why you took that step
- it's like your interview notes
- for everyone, no matter what tool you use: Excel, SQL, R, Python, whatever
- tracks everything, even as simple as sorting a column

Why:
- allows other people to fact-check your work
- for reporters, a way to show data journos what yypes of analysis you did, and vice versal.
- for readers, a way to capture your methodology. Adds transparency.
- because human memory is bad

Who is the reader?
- You:
	- if you spend a long weekend or have to leave the project for a bit.
	- if it's something updated periodically and you rerun the same analysis every day
	- _especially_ if you're the only journo in your newsroom
- your colleagues
	- program as if you're going to be quarantined tomorrow, so anyone else can pick it up
- your boss
- readers
- lawyers
- everyone

What are the formats
- Pen and paper
	- please no
- Google Docs
	- Code Blocks plugin for Gdocs: https://gsuite.google.com/marketplace/app/code_blocks/100740430168
- Excel/Google Sheets
	- comment functions: https://support.office.com/en-us/article/insert-comments-and-notes-in-excel-bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8
	- Google Sheets: https://support.google.com/docs/answer/65129?co=GENIE.Platform%3DDesktop&hl=en
- Text/Markdown files
	- https://en.wikipedia.org/wiki/Runbook
- Jupyter or Observable or R Markdown notebooks
	- Jupyter: http://www.firstpythonnotebook.org/
	- Observable: https://twitter.com/palewire/status/1084573066271682560
	- R Markdown: https://rmarkdown.rstudio.com/
	- use whatever format is also used in your newsroom, whatever's most helpful for you
- Whatever works for you and is clear to other people

Use a format that makes sense for the future reader of your work.
- Maybe your reader is an R coder, and you did your analysis in R, so leaving the data diary in the form of the comments in the code.
- Maybe your reader doesn't share a code language, so plain text is better
- Maybe your reader isn't good with the text editor, so you want to do it in Google Docs

What should it contain?
- your code/formulae
- the StackOverflow links and IRE tipsheets where you found the code
- where you downloaded the data and where you saved it
- text explaining your analysis and why you made certain decisions
- outputs of your code: what it spat out, or links to the files that were the result of the analysis.


It's not just for data journalists. It can be for anyone. Sysadmins. Statisticians. Plumbers.
