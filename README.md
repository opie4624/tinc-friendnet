tinc-friendnet
==============

FriendNET management interface for use with tinc


* Web Interface
* invite friends
* bootstrap configs
* cli/cron tool to update existing configs
* Can we generate RSA Keys or must tincd do it?
  * Should we generate the private key or just accept submission of the public?
* track who invited who
* perhaps require some network consensus or voting on invited people
  * may only work once the user base is larger
* make dns entries for in-network resolution or hosts file the cli/cron can update
  * akraut-lance.friendnet
* nodes named username-nodename
* allows users to make nodes into "super nodes" (connect lines added)
