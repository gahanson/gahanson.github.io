---
layout: card
title: Designed, implemented and deployed Ingest Package Creator for video metadata testing
section: 1
---
New Movies and TV shows are delivered to Shaw as a high quality video file and one or more xml files containing metadata such as the shows name, actors names and genre in a compressed file package.  
These files must be processed to create video files of different formats and store the metadata in Shaw servers to be delivered to customer cable boxes and streaming services to be used in the cable guide or streaming websites and apps.  
Aspera Orchestrator is used to organize and run the different workflows for the video and metadata.  
To test the workflows we needed a way to create a simulated video/xml package. The Ingest Package Creator was a CakePHP website with a front-end that allows a user to select different metadata to include in the xml file and test video files. The back-end will then create an xml file and then create a tar file containing all the package files. It then allowed the user to copy the package file to the hot folder for ingest to start.  