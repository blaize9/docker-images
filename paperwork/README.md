Paperwork - OpenSource note-taking & archiving
==============================================

<img src="https://raw.githubusercontent.com/twostairs/paperwork/master/paperwork-logo.png" width="250" align="left" />

Paperwork aims to be an open-source, self-hosted alternative to services like Evernote ®, Microsoft OneNote ® or Google Keep ®.

Paperwork is written in PHP, utilising the beautiful Laravel 4 framework. It provides a modern web UI, built on top of AngularJS & Bootstrap 3, as well as an open API for third party integration.

For the back-end part a MySQL database stores everything. With such common requirements (Linux, Apache, MySQL, PHP), Paperwork will be able to run not only on dedicated servers, but also on small to mid-size NAS devices (Synology ®, QNAP ®, etc.).

## Starting Paperwork




## Persistent data

All configration and databases is stored within the /config volume within the docker container

-	/<mydatalocation>/config:/config