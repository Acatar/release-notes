4.9.0 Release Notes
====================

>May 24, 2016

###Integration - Updated
* Adobe connect integration was enhanced with ability to create and edit meetings.
* UI added in course admin screen to perform these new tasks.

###Course Administration - Updated

* Added a dropdown option to edit the course information (name, title, etc) from the course admin screen.
* Added the abilty to set a default meeting url as part of the course information on the edit popup(used in the meeting component).
* Added a dropdown option to navigate directly to the roster of the course
* Added a dropdown option to create a new meeting room in adobe connect (visible only if the tenant has been configured to use adobe connect)

###User Administration - Updated

* Added a dropdown option to set feature flags for a user (used to hide / show buttons like 'Create Course', 'Course Administration', etc)

###Course Component - Meeting

* Meeting component displays start time, end time, 'Join Event' button presenter name (if configured), physical location (if configured).
* Start and end times are driven off the date and time set on the element.
* If a default meeting url has been set (by editing the course details) at the course level, it will be used as the url for this meeting. This url can be overridden from the component configuration.

###System Maintenance
* Minor bug fixes with dropdowns and scrolling
* Minor bug fixes with discussion component
* Security enhancements for hyperlinks
* Better error logging
