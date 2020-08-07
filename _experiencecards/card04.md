---
layout: card
title: Designed, implemented and deployed Django website to monitor Video Content ingest
section: 1
---
Needed a way to monitor the processing of metadata and video of an ingest package as it traveled through multiple Aspera Orchestrator workflows to ensure the videos are transcoded, then saved to video servers, and that the metadata was stored in the correct databases.  
Aspera Orchestrator has a REST API to access MySQL databases and running processes used while workflows are in progress. The Django website would use the API to get data on running or completed workflows and also it could save the results to a database.  
Website users would select a package name or id number and view a dashboard that displayed the individual workflows and the status of each. The status could also be compared to values saved from a previous ingest using the same package.  