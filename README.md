Nuxeo Mail Manager (Open Source)
=====================

Open Source project to add mail manager feature into a Nuxeo DM instance.

The Marketplace produced by this project add:

* a new domain to manage mail
* a check box for mail operator group into the created domain
* for each user referenced into the user directory a mail box
* Administrator can create mail boxes into the mail manager domain and affect one owner and several participant
* Administrator can create delegation object to delegate mail management of user A to a list of users. All mail management task assigned to the user A will be also affected during the existance of the delegation object.

On each document created into the mail box for mail operator a qualification/routing task is started:

* Qualification target task goal is filling the creation form associated to the document type created.
* Routing task goal is select the mail boxes where the document will be routed.

This project essentially implement the delegation logic based on the [computed groups](http://doc.nuxeo.com/x/MofZ) feature.
Other feature are implemented into the Studio project that will be soon available as Open Source Project.
