
OSM Everywhere
==============

This is an umbrela project of a set of tools around OpenStreetMap to help doing crowd-review before mass-importing, and bi-directional synchronization between Government/official data with OSM/crowdsource data.


Current idea
------------

* There should be a mapping/connection service between Gov. data <---> OSM data.
  - Gov. data is mapped to a specific version of a set of OSM features.
* There should be a notification service for 3rd parties.
  - If an OSM feature that was connected to a piece of official data is updated, the officials get a notification and can take actions to update their own dataset (accepting changes from OSM) or to keep their own version.
* There should be a crowd-reviewing platform for datasets so mappers can check the status of a piece of data:
  - If there's already a feature on OSM representing the location, a mapping should be established.
  - If the data is not on OSM yet, queries to OSM could be made to evaluate data quality (accuracy of location and information, status of surroundings, etc.)


See also
--------

* [Chia-liang Kao's original idea](https://www.newschallenge.org/challenge/data/entries/openstreetmap-everywhere).
