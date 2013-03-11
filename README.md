Forked from https://github.com/mpetroff/kindle-weather-display

/!\Work in Progress/!\

TODO:
- [ ] Install job into cron programmatically (include un-install from cron)
- [ ] Remove ugly while-loop
 
DONE:
- [x] Application turns on usbnet before running
- [x] Run as Kite application instead of "on-boot" (my kindle used to get stuck in boot loops since the framework didn't want to be killed so early)
- [x] PHP replacement for original Python and Bash scripts on server side
- [x] Use World Weather Online API and geo-location service (if, like me, you tend to move around quite a bit)
