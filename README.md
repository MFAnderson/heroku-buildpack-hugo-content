# DPS Content Buildpack for Heroku

### Context

This buildpack does not publish any content. It creates static content and moves them over to a static resources folder.
This content is then served via a SAML application. This allows for all the content to be behind TW Okta.

### Contents

* A detect script to allow for heroku to check this buildpack's compatibility with the code
* A compile script that has the code to move the appropriate content over
