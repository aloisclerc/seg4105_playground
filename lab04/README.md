## High-Level Overview:
Multiple WIP numbers are sometimes assigned to the same tag on accident. This happens when a tag is not signed out by the worker when it reaches the end of the production line. When a tag is overwritten, a feature needs to be implemented to automatically remove the old WIP number from the tag, and to ping the supervisor to manually update the end time for a specific tag since the end time is no longer accurate. The end time given by the supervisor will then be used to update the database.

