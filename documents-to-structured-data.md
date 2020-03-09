# Turning your stack of docs into structured data

Lisa Pickoff-White, KQED
Will Craft, APM Reports

Slides: https://docs.google.com/presentation/d/1-aWUuNNx0NmG4xfEwE8k31xmVE7vh14GRJmpfAgsA9I/edit
Schedule: https://ireapps.github.io/nicar-2020-schedule#20200308_turning_your_stack_of_documents_into_structured_data_2187

## This talk does not cover

- machine learning
- cleaning data
- tools to create databases
- web scraping
- FOIA

## This talk does cover

Methodology!

You need a facility to structure your data. It needs to be organized, have a data model, and needs to be easy to analyze.

## Should you make a DB?

When to make a database:
- you have a question that's guiding your document
- docs/sources will answer the question
- to make the database is a reasonable effort

When not to make a database:
- someone else already has gathered the data
- you don't know what you need from the data
- to make the database will destroy you, mind body and soul.

## How to make a database

Important to making the database is to have a hypothesis. Have a scoped, defined question. A hypothesis.

Once you have the hypothesis, determine what answers from the data will answer your question.
- what data points
- what is the quality of the data
	- what's problematic in the data? How do you solve for that?
	- what'll be easy to deal with? What's hard?
- are there other datasets you want to join to your database?
	- might start from semistructured data, then move to unstructured data

Goal is to identify trends, find characters, and tell stories.

Planning the DB in budget and scope:
- are all the data you need in the docs
- how are you going to extract the data
- what's your methodology
- what will all that take?
- will that answer the question

You _do not_ want to do three weeks' data entry before suddenly realizing it's not going to answer the question

You need a plan for data entry. **Hand entry is last resort.**
- how much data will you enter?
	- how many records?
		- limit by time range
			- why that time? Is there a natural start or end time, like a change in the law?
		- limit by geographic like count of counties
- who's doing data entry
	- how long will that take?
	- do people need training on that, or a guide?
	- keep data entry as simple as possible if you're involving people who aren't you at your best
		- use forms, rather than direct entry into Excel
		- airtable is great but $$$$
		- Google Forms
		- self-hosted DBs
- Who's doing fact-checking, and how?
	- are you doing "double entry", the gold standard?
	- spot check?
	- Who's checking? When?
- Time yourself and a colleague on testing one entry or another: this will help you anticipate how much time the whole project will take

Do a small test run!
- this helps you figure out what you've missed for making the story
- lets you do iterative development of methodology without wasting time.
- do the analysis on ~5 entries, to be sure you have what you need to do the story. See the forest composed by the trees.

It's very tempting to underestimate how long data entry will take. It'll always take 3-10x longer than you think it will. You need a realistic plan.

Write down your methodology! You will revise it over time.
- Will's version-5 methodology for one project: https://tinyurl.com/itd-methodology
- Will's final version: https://www.apmreports.org/files/peremptory_strike_methodology.pdf
- see the [data diaries](./data-diary.md) talk.

On the results of test runs:
- be up front with your editors
- time expectations are worth managing
	- time logging is great: where you're losing/spending times
- there are so many people involved in the story; figure out what communications need to be done to keep everyone in the loop. A series of memos and deadlines. Sometimes it's necessary to get everyone in a room every 2 weeks to make sure everything's progressing.
	- cross-newsroom projects include a lot of relationship management: checking in with people

## Group exercise

See [documents-to-structured-data-exercise.md](./documents-to-structured-data-exercise.md) for working notes on the exercise.
