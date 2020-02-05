# AP-Wiki-Windows-Automated-Install-and-Build

One click install and build of Ardupilot wiki on windows with cygwin.
- Download file, right click and select "Run with Powershell"

Notes:
- Tested successfully on win 10
- Incompatible with win8.1. and 7
- Can be run on top of existing cygwin install (eg with previous cygwin Ardupilot sitl build) 
- If ~/ardupilot_wiki directory exists it will not be overwritten.
- Will take some time depending on Internet download speed and windows machine, ymmv:  A bit under 3 minutes with 60mbps DL speed and Skylake Corei7, 7 minutes with 2014 low end Ivy Bridge Corei5 laptop to give you an idea.
 - Only builds copter and plane wiki sections, other sections or entire wiki left optional as this takes significant additional time.
 - Powershell doesn't like disabled firewall. If script doesn't run and you get a "There are no more endpoints available from the endpoint mapper" error it's very likely to be because of that.
  
- Please consider as beta at this time.
- See also: http://ardupilot.org/dev/docs/common-wiki_editing_guide.html
  
