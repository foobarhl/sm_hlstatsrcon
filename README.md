sm_hlstatsrcon
==============

This plugin provides Limited RCON access to an HLStatsX server.  Specifically
it  maps a new password to an HLStatsX server IP and limits command access to 
basic commands needed by stats. 

== Configuration ==

Autocreates cfg/sourcemod/plugin.sm_hlstatsrcon.cfg

sm_hlstatsrcon_ipaddress : IP Address of the HLStats collector
sm_hlstatsrcon_password  : Custom password for this host to use for RCon.  Do NOT use your main rcon password!

