**Story**
I want to monitor a local folder for new content. When a new file becomes available, the system will check if it's either an MP4 video file or an XML file. If it's an MP4 video, the system will then search for a corresponding XML file with the same name. Upon finding the XML file, it will extract metadata such as title, description, and tags. Subsequently, the system will upload the video file to an Online Video Platform (OVP) along with the extracted metadata. To prevent duplicates, before processing a new file pair (MP4 and XML), it will verify whether the pair has already been processed.

![image](https://github.com/josev2046/WatchFolderAutomation/assets/15835851/c228c1f9-8c00-4fdc-b713-2e6c1023c2f0)

**Purpose**
Purpose: A watch folder serves as a designated directory that is monitored by a specific application or process. The primary purpose of a watch folder is to automate tasks based on the contents of that folder, facilitating Automated File Processing, Workflow Automation and Data Ingestion.

**Context**
In the context of digital content migration, this blueprint serves as a guide for facilitating bulk media and metadata ingests.
