SIMPLENEWS SCHEDULER
===========

CONTENTS OF THIS FILE
---------------------

 - Introduction
 - Requirements
 - Installation
 - Permissions
 - Usage
 - Sponsors

INTRODUCTION
------------

If you use the Simplenews module for sending out your newsletters, this module adds scheduling functionality to your site.

The Simplenews Scheduler module allows you to send a newsletter as a re-occurring item
based on a schedule. It does so by creating a new "edition" (rendered copy as HTML Format)
of a node at the time that it required to be sent again.

The editions have an extra tab (for those with permissions) for viewing all editions as well as
the original newsletter they are generated from. The original newsletter is never sent but all
editions are according to a pre-defined schedule which is triggered via cron and can be
defined when you create or edit a simplenews node.

Current options for sending are by day, week, and month.

To submit bug reports and feature suggestions, or to track changes:
http://drupal.org/project/issues/simplenews_scheduler

TESTED
-----

@todo
This module has NOT BEEN TESTED and is being ported to Backdrop.  It may work.

KNOWN ISSUES
---------------------
@todo


REQUIREMENTS
------------

* Simplenews module
* Date module

-- RECOMMENDED --

* SuperCron module - http://drupal.org/project/supercron

INSTALLATION
------------

Simplenews Scheduler can be installed via the standard Backdrop installation process
(http://drupal.org/documentation/install/modules-themes/modules-7).

* Install as usual, see http://drupal.org/node/70151 for further information.

PERMISSIONS
------------

@todo


USAGE
-----
@todo

Locate the module options under "Send newsletter" on the node edit page. When you select
"Send newsletter according to schedule" a new section titled "Schedule details" appear.

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

Maintainers
-----------

- seeking

Current Maintainers on Drupal:

* Leigh Morresi (dgtlmoon) - <http://drupal.org/user/25027>
* Gabor Seljan (sgabe) - <http://drupal.org/user/232117>

Ported to Backdrop by:

 - biolithic <https://github.com/biolithic>
