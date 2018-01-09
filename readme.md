# PJAX-Standalone#

A standalone implementation of push state AJAX, designed for use on non-JQuery web pages.
The design is loosely based on the original jQuery implementation found at: https://github.com/defunkt/jquery-pjax.
Currently this repo is just fork of https://github.com/thybag/PJAX-Standalone

### What changed?
* Fixed bug with invalid page title (No using 'data-title' now)
* Renamed events
* Added new one event to detect when pjax load blocked by plugin.

### Callbacks

PJAX-Standalone implements the following callbacks/events:

* pjax_load_requested - Called before AJAX request is made
* pjax_load_ended - When AJAX request has completed
* pjax_load_success - When AJAX request has completed successfully
* pjax_load_failed - When AJAX request did not complete successfully (error 404/500 etc)
* ready - Fired when PJAX completes initial link parsing
* pjax_load_blocked - Fired when AJAX request blocked by client. For example - requested same link as we are at.









	
