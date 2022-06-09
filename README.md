# Twitter Context Annotations

This repository contains a flat file (csv) of the available context entities supported by the [Tweet Annotations](https://developer.twitter.com/en/docs/twitter-api/annotations/overview) feature of the Twitter API. The file contains a list of "evergreen" entities (non event-based entities that are always active and annotating Tweets) encompassed by the 80+ supported domains that have annotated Tweets in the past few months. See additional details on the file below:

* Column headers: domains, entity_id, entity_name
  * Note: the "domains" column can contain one or more values. In the case of multiple domains, the value will be wrapped in double quotes (e.g., "10,56,131")
* File format: CSV
* File size: ~7 MB

Feel free to download the file(s) in this repository to discover the available context annotation entities. We aim to provide an updated file ~quarterly to encompass new entities that have been added – so please check back in a few months if you desire updates.
