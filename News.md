# 17th Feburary 2011 #

Hello there :D I have updated the images.zip (The Cache) to be the most current. I am also working on updating the addon for future XBMC compilance. Feature wise it will be dry, as I still don't know what else to add. Suggestions are welcome as always!

# 28th September 2010 #

And this is just an example of how fast things move sometimes :)
Version 1.0.3 just got the pull request where we changed names to: Tool-assisted Superplays
The Icon was also changed :)
Enjoy

# 27th September 2010 #

I just worked some more on the addon, as always, you can find the latest changes in the SVN.

I fixed the international language support (it crashed before) and also made the translations for german and french.

In a few hours we should ammend the changes to the spanish langauge in the SVN trunk and if nothing new comes up, we will do the pull request over at XBMC :)

# 25th September 2010 #

Hello again!

I just fixed both bugs (date & linux crash) and updated the SVN with the new source.
The Pull request to XBMC has been sent, so in a couple of hours, 1.0.1 will have deployed to the official repository :)

Enjoy!

# 24th September 2010 #

Well, this is embarassing... I just realized we have two major bugs in Version 1.0.

The first being the date (and thus, sorting by date) being erroneus (or just non-working); I never made sure of using double digits when submitting the date and thought XBMC could handle that fine, but apparently, it does not :)

I fixed this already and it is available in the SVN trunk.

The second bug, is only present in linux... Apparently it doesn't work to download the thumbnail cache. I have not yet received an error log and do not have a linux version of xbmc up and running to test and debug that. I will look into solving that issue as well before I release 1.0.1 which is then the true 1.0 :)

I will most likely end up fixing this bug in the following days, but we shall see :) No promises!