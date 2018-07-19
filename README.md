# openEQUELLA Office Integration

The Office Integration for openEQUELLA is a standalone application for Windows that historical was 'included' as a download link in openEQUELLA.  This download link has now been removed, but the functionality is still possible.  

Due to licensing issues with the ```Office.dll``` artifact, the ```Office.dll``` had to be removed.  

To build the ```msi``` installer binary:
1. Obtain an updated ```Office.dll``` from Microsoft and place in ```/EquellaOfficeScrapbookIntegration/Lib```.  History in [Equella#98](https://github.com/equella/Equella/issues/98).
1. Build the project as an ```msi``` installer on a Windows machine
