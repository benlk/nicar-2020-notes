# How to build a live data-driven application that never crashes

https://ireapps.github.io/nicar-2020-schedule#20200307_how_to_build_a_live_data_driven_application_that_never_crashes_2171

GitHub: https://github.com/TylerFisher/nicar20
Slides: https://docs.google.com/presentation/d/16iYbBlPa2pOwUjRTKzUT2siucrSCNIUzdyFcU_A0kVg/edit#slide=id.p

## Presentation

On caching:

- in-memory caching is good when:
	- you're making lots of updates to a dynamic page
- reverse proxy caches (Cloudflare):
	- great with static assets that change infrequently

Caching makes sense if:
- you have a budget with a prod server that can deal with all the traffic
- you're okay with pages being minutes behind due to caching
- you can maintain a server, through budget or time

If you don't have a server, you can't cache. 

So let's talk about serverless architecture. It's a way to use a major cloud provider's server to 1) spin up a server 2) run the function 3) destroy the server, without your intervention. Two versions are Amazon Lambda, and Google Cloud Run. Good when:

- If you don't need to maintain backend state, serverless is great.
- your backend needs can be broken into individual functions
- you won't run functions often, because they can get expensive with frequent runs.

https://burkeholland.github.io/posts/laws-of-serverless/

If you're updating the site frequently &mdash;

Let's talk about static websites! HTML, CSS, JS: no backend. No database powering the website.

- cheap to host
- isolate your backend env so that reader traffic never touches the backend
- easily archived


## Using the repo

Here's the repo again: https://github.com/TylerFisher/nicar20
- requires pipenv
- is a Django app
- Django has a concept of "projects" and "apps", where a project can contain multiple apps
- start from Quickstart
