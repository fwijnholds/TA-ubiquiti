This add-on has partially been powered by the Splunk Add-on Builder. 

This TA for Ubiquiti was developed for an environment with CloudKey, UDM Pro, USG and Pro AP.  This release supports field extractions for the Firewall and DHCP facilities. It requires 3 indexes; UBQT, netdhcp and netfw. The net* indexes are there for CIM compliance

Changelog:

Added sc_admins to default.meta for compatibility with Splunk Cloud
Corrected and added CIM fields and made jQuery 3.5 compliant			              09 May 2022
Added support for wireless connects and disconnects, Edgeswitch link changes    30 Apr 2019
Added sourcetype and extractions for linkspeed checks                           12 Apr 2019
Fixed FW rule extraction, Sourcetype renamed from everything ubqt to ubnt       11 Apr 2019
Added support for the BETA IPS functionality					                          13 Oct 2018
Normalized mac address reporting for hostapd					                          30 Aug 2018	
Improved hostapd extractions						                                        29 Aug 2018	
Improved hostapd sourcetyping and added field extractions.			                29 Aug 2018	
Got approved logos from the vendor.https://www.ubnt.com/marketing/#logos	      07 Aug 2018

Special thanks to Corey Falo at Ubiquiti for his support, and Paul Jeffery at Splunk for his input! 
For any questions or future suggestions, please contact Michael Nobles at mnobles@splunk.com
