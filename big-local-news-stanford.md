# Big Local News

Biglocalnews.org

Big Local News is a project from Stanford. Trying to knit together key patners, tools, and platforms, by:

- giving local journalists tools to do things
- giving non-journalists opportunities to share data with journalists

Tools:
- FIPS tool, allowing journalists to populate a CSV with state/county/etc FIPS codes.
- [Archive data upon publication](http://biglocalnews.org/), shared to the public and backed up on Stanford's private clouds.
- They already have Datasette as an available plugin, but there'll be more, hopefully.
- There's an API, which supports GraphQL
- Audit trails
- Presently authenticaing users via Google's Oauth, but there'll be eventual support for Press Pass, an SSO suite for journalism tools.
- Auto-expiring 24h links to files
- Access controls by user account

They don't yet support versioning of files that are uploaded.
