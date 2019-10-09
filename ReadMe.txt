Read Me for ZoneMigrator Utility
Current version is for 64 bit OS (Windows 10 and windows7)

Please unzip the ZoneMigrator.zip; Folder with name ZoneMigrator  will be created
Now launch the ZoneMigrator.exe application and browse your Input File with cfgshow output from Brocade switch.

before you start conversion, optionally you may specify these:
*Output File location and file name
*Different VSAN number in allowed VSAN range
*Select Zone mode as Enhanced
*Select Device-alias mode as Enhanced

At the moment we are only supporting pwwn based zones. Any hard / interface based zoning will error out and provide errors in the generated log files.

You may optionally create a shortcut on your desktop or your preferred location for "ZoneMigrator" application.

1.	This tool is designed specifically for non-DCNM customers. We are looking at BRCD customers for whom DCNM is a foreign element. We don't want them to install, configure / learn DCNM just for migration.
2.	We are designing this tool to target smaller customers. For enterprise customers, we highly recommend AS services who are experts at all expects. 
3.	This is not a duplicate of DCNM. Once we have a working tool, we probably will try to integrate it with DCNM but that is the future roadmap. 
4.	This tool is a functional tool but there is no support to this tool. The engineering team will help us address any major concern and re-visit tool as needed but we can't maintain / support this on regular basis.
5.	This tool is tested only for BRCD switches with FOS 7.x and 8.x releases only. This tool is not tested on anything else.
6.	At the moment, this is supported only on 64-bit Windows 7 and 10 version. If you have MAC, please try this on Fusion or on lab windows machine.
  

For any feedback, please send an email to: mds-zone-migration@cisco.com

