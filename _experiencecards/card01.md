---
layout: card
title: Translated manual test cases for Gateway and BlueskyTV cable boxes to Python scripts
section: 1
---
Control cable boxes using the Accenture StormTest product consisting of a rack of IR controllers connected to a Windows Server PC with HDMI inputs running the Storm Test software.  
The Storm Test software has a Python API to control a CPE box, measure the Video and Audio from the HDMI inputs and perform actions such a OCR for portion of the video signal.  
Manual testers will use a cable box, remote and TV at their desk to follow test case procedures to verify Gateway and Bluesky software was working properly on the CPE’s.  
We translated procedures posted by the manual testers to the department HP ALM instance (HP Application Lifecycle Management is a set of software tools developed and marketed by Micro Focus for application development and testing. It includes tools for requirements management, test planning and functional testing, performance testing, developer management, and defect management.) into a Python script that could perform the same verification or test using the Storm Test product.  