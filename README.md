What Is This
================

This is a template used by reupholster to generate a couchdb couchapp.
For more information about using reupholster, see 

http://reupholster.iriscouch.com/reupholster/_design/app/index.html



What To Change 
======================

reupholster.json  - change the couch, test-couch, and stages to match your flow

app.js - This becomes main main design document. Add shows, views, lists, filters, etc.

Folders
=======

html - All files in the html folder are your root application. They will get put as attachments on _design/app.

tests - BDD style tests that run in Firefox locally, and HTMLUnit on a CI server. 

docs - Any couchdb docs you want to have available to the application. You can add additional design docs with this structure:
docs/_design/app2.json
docs/_design/app2/index.html







