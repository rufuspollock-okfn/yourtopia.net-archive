Static site archive of yourtopia.net which ran "live" from January 2011 to
March 2013.

At some point we hope to reboot YourTopia.net to run off the "new" yourtopia
codebase which powers italia.yourtopia.net.

## Steps for archiving

Archiving was straightforward as the main display page (result) fortunately
inlines all its data.

Mirror the site:

    wget -mpc -R --user-agent="" -e robots=off yourtopia.net

Then make all pages into directories so links still work.

