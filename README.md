# arcana-module-zero
Portage tree automated sanity check tool/bot

arcana is the name of my bot on freenode. The idea is to
hook up an alert system to IRC and any other chat service
/bugtracker that might be used in the future.

The basic interface is going to be (json) log dump to an autoindex 
http server. No XML support is planned, since anyone who likes XML
that much should be able to convert JSON -> XML.

