---
layout: post
title:  "T-Pot - Important Update Notification "
date:   2015-10-23 13:37:42
categories: feature
tags: featured
image: /assets/images/docker.jpg
---


Last spring we released T-Pot and ever since, Docker evolved rapidly with new versions, new features, and eventually a new repository. With regards to early releases of T-Pot and the fast development of Docker, we manually pinned the Docker versions used to the 1.5.x and 1.6.x branches. Now, with the latest Docker releases and Dockers' switch to a new repository for Ubuntu (and deprecating the one we have been using), we updated the T-Pot ISO and the GitHub project accordingly.

So, from now on, we will stick to the latest Docker version.

*But, why is this important to you?*

Well, Docker deprecated their old versions and will no longer serve images to old versions. So you will have to update in order to keep the system fully functional.

If you want to upgrade your existing installation you can download [this upgrade script](https://github.com/dtag-dev-sec/tpotce/blob/master/upgrade.sh):
1.	Login to your T-Pot as tsec and execute the following commands, **but only run the script once**!

		git clone https://github.com/dtag-dev-sec/tpotce.git
		sudo tpotce/./upgrade.sh

2.	If everything worked fine the machine will reboot.

3.	Check if your containers are running correctly by either by pressing CTRL+F2 or by logging in as tsec and sudo status.sh.

Otherwise, if you wish to perform a new installation you can download the new ISO [here](http://community-honeypot.de/tpotce.iso).


In case you encounter any problems, feel free to post an issue [here](https://github.com/dtag-dev-sec/tpotce/issues). 

 
