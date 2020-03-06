# Library, from the New York Times

Library is backed by Google Drive, because people know how to use it.

Demo: https://nyt-library-demo.herokuapp.com/
GH: https://github.com/nytimes/library
Customization example: https://github.com/nytimes/library-customization-example
Google GrouP: http://tinyurl.com/nyt-library-community
Newsnerdery.org Slack: #proj-library


It's a nodeJS app wrapping the Docs API.
- docs stored in a particular folder are traversed
	- has options for subfolders
	- tags in filenames with `| tag` postfix on file name: https://nyt-library-demo.herokuapp.com/how-to-use-library/how-do-i-use-tags
	- yes, you can move other docs into Library
- It parses and caches docs html
	- links to other google docs are interpreted to links to the relevant Library page
	- formatting (bolding, underlines, headings) are kept
	- https://nyt-library-demo.herokuapp.com/how-to-use-library/supported-formats
- has a search scoped just to Library docs.
- It has a "intuitive and clean layout" and it's open source.
- access controls on document edits are done via Google Drive:
	- blanket read access
	- write protection isn't really a thing, beyond Google Drive's edit permissions
- access controls to read the Library site itself can be done via Google's Oauth
	- it's designed to support having a public website for private docs: require login
	- it's the `APPROVED_DOMAINS` variable
	- only people with an email address from your G Suite can be authed, or you can set it to specific email addresses
- Deployed via Heroku
	- nothing in Terminal; it's all via web browser!
	- base level is free
	- could maybe also be done via Glitch
- customizeable via the `custom` directory
	- https://github.com/nytimes/library/blob/master/custom/README.md
	- https://github.com/nytimes/library-customization-example



My questions:
- [ ] can it be kept password-protected?
	- can be locked to specific domains access via Google's auth

Setup notes:
- It's got a Google Drive integration, so you must cteate a GCP project https://nyt-library-demo.herokuapp.com/get-started/create-a-google-cloud-platform-project
- And create a "service account", which has access to the docs in the Drive
- Optional reader history via Google Cloud Data Store
