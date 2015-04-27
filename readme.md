SIMPLENEWS SCHEDULER
===================

CONTENTS OF THIS FILE
---------------------

 - Introduction
 - Tested
 - Known Issues
 - Special Thanks
 - Requirements
 - Installation
 - Coming From Drupal?
 - Usage
 - License
 - Credits
 - Maintainers

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

<<<<<<< HEAD
Email Modules
The following modules ported to Backdrop are inter-related to the mailing system:

simplenews

simplenews_scheduler

mimemail

mandrill

mailsystem

smtp

They have been converted from Drupal to Backdrop but are still not working.  They need debugging into what was changed between the systems and how to fix it. I, biolithic the one who did the intial conversion, lack the heart or time in the spring of 2015 to debug them currently.

Do you have a need or desire for email newsletters?  You are welcome to submit pull requests to finish these modules.  It may not be a lot of work.  Thanks!
=======
@todo

This module is not working in Backdrop yet.  Node and Taxonomy conversions need to be made (among possible other things) before it can be tested.
>>>>>>> f1408dca6536d0cdba79105c4e8c67bea9741a37

KNOWN ISSUES
---------------------

@todo

SPECIAL THANKS
--------------

the creators of the Simplenews module

REQUIREMENTS
------------

* Simplenews module
* Date module

-- RECOMMENDED --

* SuperCron module - http://drupal.org/project/supercron

INSTALLATION
------------

Install this module using the official Backdrop CMS instructions at https://backdropcms.org/guide/modules

* Install as usual, see http://drupal.org/node/70151 for further information.

COMING FROM DRUPAL?
-------------------

Nothing substantially different.

PERMISSIONS
------------

@todo


USAGE
-----

Locate the module options under "Send newsletter" on the node edit page. When you select
"Send newsletter according to schedule" a new section titled "Schedule details" appear.

LICENSE
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.

CREDITS
-----------

This module is based on the Simplenews Scheduler module for Drupal, originally written and maintained by a large number of contributors, including:

- Leigh Morresi (dgtlmoon) - <http://drupal.org/user/25027>
- Gabor Seljan (sgabe) - <http://drupal.org/user/232117>

MAINTAINERS
-----------

- seeking

Ported to Backdrop by:

 - biolithic <https://github.com/biolithic>
