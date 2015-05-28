# StormForce XR #

StormForce XR is a free open source program written in [Python](http://www.python.org/) which connects to a [Boltek LD-250](http://www.boltek.com/ld250.html) and/or [Boltek EFM-100](http://www.boltek.com/efm100.html) lightning detector and displays lightning strikes in real-time on your desktop delivered via [XMLRPC](http://www.xmlrpc.com/).  Developed and tested with [FreeBSD](http://www.freebsd.org/) but should work with Linux and other POSIX environments as well as MS Windows.

Re-written using the v0.6.0 codebase of StormForce, StormForce XR has been split into two components - the server side and the client side.  External packages have been reduced to just **FIVE** (with only one being optional) - [serial](http://pyserial.sourceforge.net/) (server only), [pygame](http://www.pygame.org/) (client only), [psycopg2](http://www.initd.org/psycopg/) (server only), [twisted](http://twistedmatrix.com/trac/) (server only), and optionally [matplotlib](http://matplotlib.sourceforge.net/) (client only) to simplify installation.  The server side alone can provide a external (third-party) application access to the StormForce engine and dataset via [XMLRPC](http://www.xmlrpc.com/), this means you can write your own client application which talks to the server should wish to do so.  Everything is written to a [PostgreSQL](http://www.postgresql.org/) database so you can always talk to that directly should you feel the need to.

Please report any bugs using the [issues](http://code.google.com/p/stormforce/issues/list) section.


**NOTICE:** StormForce XR usually gets work done on it during the spring/summer months in the UK (around April-September) - this allows me to test the code with real storms and I can compare my data with other stations.  So during autumn/winter the project will be very quiet.


---


Status: **Beta**

Supported OS: **[FreeBSD](http://www.freebsd.org/), Linux, and Microsoft Windows**

Supported Hardware: **[Boltek LD-250](http://www.boltek.com/ld250.html), and [Boltek EFM-100](http://www.boltek.com/efm100.html)**

Need Testers for: **Mac OS, Solaris, BeOS, and more!**




---


---


## StormForce ##

StormForce is a free open source program written in [Python](http://www.python.org/) which connects to a [Boltek LD-250](http://www.boltek.com/ld250.html), [Boltek EFM-100](http://www.boltek.com/efm100.html), and/or a [Boltek StormTracker (PCI)](http://www.boltek.com/stormtracker.html) lightning detector and displays lightning strikes in real-time on your desktop. Developed and tested with [FreeBSD](http://www.freebsd.org/) and Linux but should work with other POSIX environments as well as MS Windows.


---


Status: **Stable (Deprecated) - _No longer under development or support (StormForce XR supersedes StormForce which is now end of life)  Don't worry, you can still grab it from the [downloads](http://code.google.com/p/stormforce/downloads/list) section._**

Supported OS: **[FreeBSD](http://www.freebsd.org/), Linux, and Microsoft Windows**

Supported Hardware: **[Boltek LD-250](http://www.boltek.com/ld250.html), [Boltek StormTracker (PCI)](http://www.boltek.com/stormtracker.html) (Linux-only until driver is ported to other OS'es), [Boltek EFM-100](http://www.boltek.com/efm100.html), and GPS (NMEA 0183)**


---


---


## BoltekEmu ##
BoltekEmu is a free open source program written in Python which emulates a [Boltek LD-250](http://www.boltek.com/ld250.html) and a [Boltek EFM100](http://www.boltek.com/efm100.html) onto a given serial port.  Designed for the purpose of testing Boltek-based applications without the need for the actual hardware.  Developed and tested with [FreeBSD](http://www.freebsd.org/) and Linux but should work with other POSIX environments as well as MS Windows.

Only requires **ONE** external package to run: [serial](http://pyserial.sourceforge.net/).


---


Status: **Stable**

Supported OS: **[FreeBSD](http://www.freebsd.org/), Linux, and Microsoft Windows**

Emulated Hardware: **Boltek LD-250, and Boltek EFM-100**

Need Testers for: **Mac OS, Solaris, BeOS, and more!**


---


---


### Don't forget to download ###

  * **(All)** [7zip](http://www.7-zip.org/) - To extract the files from the archive.
  * **(Windows)** [Notepad++](http://notepad-plus-plus.org/) - Use for editing/viewing the text files.

---

### My other projects ###

  * **(Unix)** [DanZFS](http://code.google.com/p/danzfs/) - My own take on providing a Python backend to ZFS for monitoring (additional features like snapshots, etc will come later)
  * **(All)** [DDP](http://code.google.com/p/ddp/) - My own protocol designed to replace the aging packet system using cheap off-shelf-equipment (no TNCs needed).  Uses [fldigi](http://www.w1hkj.com/Fldigi.html) as it's "starting point".
  * **(Unix)** [DDV](http://code.google.com/p/ddv/) - My own version of digital voice which uses DDP as it's transport layer, currently only supports unix-like operating systems.


---


---


### News ###

---

15th March 2014 - StormForce XR v0.5.0 released!
  * Well, it has been quite a while since I've done anything.  This update is quite a large one with various bug fixes and new features, be sure to take a look at the README file.  Since mid-January 2014, Google Code no longer allows me upload my code to them using the downloads feature, so instead of using the "Downloads" tab above you can grab it from [here](https://drive.google.com/folderview?id=0B55A8VYdnmbOVHZxa3RlSEg3NW8) instead or the "New Downloads" link on the left hand side.


---

25th January 2014 - News
  * It's been nearly two years since I've even made any changes to the code, that is no longer the case.  Few improvements and fixes coming up in the next update.  Watch this space!

---

24th September 2013 - Not much going on, still...
  * Well, only one small storm rolled it way this year.  Not a lot.  I've had nothing to add to SXR so far this year.

---

1st February 2013 - Not much going on...
  * Eeyup, nothing much going on in SXR at the moment.  We'll see how it goes this year...

---

8th September 2012 - Softpedia awards, bolt out of the blue!
  * StormForce XR v0.4.1 has been awarded the "100% FREE award granted by Softpedia" - Check it [out](http://mac.softpedia.com/progClean/StormForce-XR-Clean-123737.html).
  * BoltekEmu v0.1.2 has also been awarded the "100% FREE award granted by Softpedia" - Check it [out](http://mac.softpedia.com/progClean/BoltekEmu-Clean-123738.html).
  * Looks like they tested it on Mac OS, wished they send me the installation details so I could update the README file!  Wonder if they are going to test [DDP](http://code.google.com/p/ddp/) and [DDV](http://code.google.com/p/ddv/) as well?

---

4th August 2012 - Upcoming updates
  * Updates for [DDP](http://code.google.com/p/ddp/) and [DDV](http://code.google.com/p/ddv/) coming soon!  Maybe even a SXR one.  Watch this space!

---

12th May 2012 - StormForce XR v0.4.1 released!
  * This release contains various tweaks and fixes to the tracking engine as well as a new strike shape for the client.  As always please read the README file for more information.

---

6th May 2012 - StormForce XR v0.4.0 released!
  * This release is a big one.  Main new features include a rewrite of it's persistence tables (now completely gone). strike history graph, and many more.  Please read the README and XMLRPC files for more details.  Hope you all like it!

---

2nd May 2012 - News
  * A big update is on the way, estimated in about a weeks time.  Watch this space!

---

23rd April 2012 - StormForce XR v0.3.1 released!
  * Here is another release which contains improvements made to the storm tracking code and new XMLRPC calls.  Please read the README and XMLRPC files accordingly for more information.

---

19th April 2012 - StormForce XR v0.3.0 released!
  * Been a while since I've done a update!  This release now uses [twisted](http://twistedmatrix.com/trac/) for it's XMLRPC service, this is now a dependency.
  * It looks like it will be possible to support the new Boltek [LD-350](http://www.boltek.com/ld350.html) with StormForce XR.  Just waiting for more information back from Boltek.  Watch this space!

---

30th March 2012 - New unit from Boltek
  * Boltek have released a new unit called the [LD-350](http://www.boltek.com/ld350.html).  Looks like a nice upgrade from the [LD-250](http://www.boltek.com/ld250.html) and appears to be able to differentiate the strike type as well.  I couldn't find any information on it's protocol (it has a ethernet, USB, and a GPS port - no RS-232) so I fired off an e-mail to them to see if I can get it supported under StormForce XR - Watch this space!

---

25th January 2012 - 100 downloads!
  * Wow, 100 downloads of StormForce XR v0.2.2.  Keep them coming!

---

27th August 2011 - News
  * The update of [DDP](http://code.google.com/p/ddp/) has been released which contains the [XMLRPC](http://www.xmlrpc.com/) proxy server and client which works with **any** XMLRPC-based client.

---

12th August 2011 - StormForce XR v0.2.2 released!
  * Here is another release of SXR this week.  Contains a new mini version of client suitable for using over [DDP](http://code.google.com/p/ddp/) or if you just need text-based information from the SXR server.  Also contains a couple of tweaks, check out the README file for more information.
  * A update of [DDP](http://code.google.com/p/ddp/) is coming up next as it contains a [XMLRPC](http://www.xmlrpc.com/) proxy server and client which works with **any** XMLRPC-based client so that it can communicate using [DDP](http://code.google.com/p/ddp/).  Keep an eye out of the [DDP](http://code.google.com/p/ddp/) website.

---

10th August 2011 - StormForce XR v0.2.1 released!
  * Here is the next version of SXR: contains a few more tweaks for both the server and the client component.  As always, read the README file for the list of all changes.
  * StormForce XR now supersedes the original StormForce, no development or support will be offered to StormForce from now on.

---

7th August 2011 - StormForce XR v0.2.0 released!
  * The next version of SXR is now available for download.  Only one main change in which the database backend has been moved to [PostgreSQL](http://www.postgresql.org/), also contains an improvement in detecting when the receiver stops responding - check out the README as per normal.  Hope you all like it.

---

4th August 2011 - News
  * I'm going to move the database engine from [MySQL](http://www.mysql.com/) to [PostgreSQL](http://www.postgresql.org/) in the next version.  Watch this space!

---

17th July 2011 - News
  * Nice to see a slight pickup of downloads for SXR - keep them coming!
  * Still haven't completed the FreeBSD driver for the [StormTracker PCI](http://www.boltek.com/stormtracker.html) yet, been on with other things...

---

30th May 2011 - News
  * Robert Boll from [Boltek](http://www.boltek.com/) has contacted me regarding the [StormTracker PCI](http://www.boltek.com/stormtracker.html) driver for FreeBSD and has given it a all clear.  Thanks Robert.
  * At this point in time, the pure Win32 client of StormForce XR is on hold so I can spend that time working on this driver.  Plus I need to keep [DDP](http://code.google.com/p/ddp/) going as well...

---

28th May 2011 - News
  * I've contacted [Boltek](http://www.boltek.com/) about me making a FreeBSD driver for the [StormTracker PCI](http://www.boltek.com/stormtracker.html), I'll keep you all posted.

---

27th May 2011 - StormForce XR v0.1.3 released!
  * Now works correctly when running under Microsoft Windows.  Instructions for getting StormForce XR working under Windows is in the README file.

---

23rd May 2011 - BoltekEmu v0.1.2 released!
  * Now works correctly when running under Microsoft Windows.  You only need to download two packages to run this, details are in the README file.
  * I'm also looking at writing a StormForce XR client (maybe the server) for Windows written in dotNET.  Hmmm...

---

22nd May 2011 - StormForce XR v0.1.2 and BoltekEmu v0.1.1 released!
  * Here is the next release of StormForce XR contains corrected code for handling the Boltek EFM-100.  As per normal, take a look at the README file.  Hope you all like it.
  * BoltekEmu now has emulation code for the Boltek EFM-100.

---

21st May 2011 - StormForce XR v0.1.1 and BoltekEmu v0.1.0 released!
  * Here is the next release of StormForce XR which now includes the client program.  As per normal, take a look at the README file.  Hope you all like it.
  * I've also developed a program which can emulate the Boltek LD-250 in software.  This is very useful for developing applications and/or testing.  Grab it from the download section and take a look it's README file.

---

16th May 2011 - StormForce XR v0.1.0 released!
  * The next generation of StormForce is now available for download.  Named StormForce XR in which XR stands for XMLRPC, currently only the server component is complete.  Will be working on the client code next, just thought it would be best to do a release.  Be sure to read the README for additional information.

---

14th May 2011 - News
  * Wow, it's been a while since I've put any news up on here!  I'm looking at updating StormForce which allows better headless operation, this would also make it more usable for external clients.  This would lead to sending strikes information via [DDP](http://code.google.com/p/ddp/).  Watch this space!

---

18th November 2010 - News
  * Still nothing new to report, been working on my GMSK modem for [DDP](http://code.google.com/p/ddp/) and [DDV](http://code.google.com/p/ddv/).

---

8th August 2010 - News
  * Nothing new to report, been spending more time on the [DDP](http://code.google.com/p/ddp/) project.

---

6th June 2010 - StormForce v0.6.0 released!
  * Here we go, the next release of StormForce.  Contains bug fixes and no longer has support for SQLite.  Check out the README first as per normal.  Let me know if you find any problems with it!  Don't forget that this release does NOT have the SSBT and Blitzortung code.
  * Versions 0.5.3 and older have been marked as deprecated and will not show on the download list.  If you want them change the search dropdown to "All downloads" then press "Search" to show everything.
  * On a side note, I have now released the first version of [DDP](http://code.google.com/p/ddp/)

---

5th June 2010 - News
  * Well, well, well - appears StormForce is still quite popular with now over 250 downloads!  Thank you all!
  * I'll see if I can release the latest code earlier, but without SSBT and Blitzortung code.

---

21st February 2010 - News
  * New project created - [DDP](http://code.google.com/p/ddp/) - for fellow amateur (ham) radio users.

---

10th February 2010 - News
  * Well, I haven't had an awful lot of time for StormForce due to my new hobby - Amateur (ham) radio, especially using PSK31 on QRP.  As I've mentioned before, I haven't forgot about StormForce.
  * We've had over 220 downloads of the latest version since it was released.  I'm quite impressed.  Thanks to you all!

---

23rd May 2009 - News
  * Woah!  It's been a while since I've posted any updates or any news.  We've now had over 120 downloads of version 0.5.4 of StormForce.  As for an update I haven't had any time to do any coding, busy busy busy!
  * On a side note, if you are having problems compiling/running the Boltek driver for the StormTracker - hold on tight!  This problem has been fixed and will be released as soon as I can.  Thanks to the Boltek-Linux developer for sorting this out as quick as lightning!

---

1st March 2009 - General news
  * Sorry for the lack of updates, been very busy.  I am trying to get the Blitzortung data uploading working (just struggling for time), when I get the code done for that I'll release v0.6.0.  However, it WON'T contain the SSBT code (mentioned earlier) which will be released at a later date.

---

3rd January 2009 - Upcoming release - v0.6.0
  * The next release will also see support for sending your strike data to blitzortung.org!  Many thanks to Egon for providing me with the details I need to do this.

---

24th December 2008 - Upcoming release: v0.6.0
  * The next release will include SSBT - StormForce Strike Bi/Triangulation.  This is step forward to create your own triangulated-based strikes.  This version will only combine the output from a LD-250 and a StormTracker, hopefully I can improve upon this to create triangulated strikes from several StormForce clients.  This is going to take some time, so bare with me!
  * The next release will also see support dropped for SQLite.  So you will either need to move your database to MySQL or don't upgrade.  You could always connect up multiple versions of StormForce if you want to!

---

11th December 2008 - StormForce v0.5.4 released!
  * Here the next version which has some minor tweaks including a different font for the strike totals.  Nothing major has been added, just thought it was time to send out an update!

---

10th December 2008 - Another new project!
  * I've started yet another project!  This project aims to display weather data from a Oregon Scientific WMR928 Weather Station and display it on your desktop.  Hope you all [like](http://code.google.com/p/wmr928/) it!

---

23rd November 2008 - StormForce now marked as STABLE
  * I've now decided that StormForce is stable enough to be marked accordingly.

---

18th November 2008 - New project!
  * I've started another project which when combined with StormForce provides excellent notification of close/severe alarms - Introducing [GSMSMS](http://code.google.com/p/gsmsms/), created so you can send SMS messages from your GSM modem.  Hope you all like it!

---

16th November 2008 - News...
  * Still no updates I'm afraid - however, I'm looking into using M2Crypto to provide encryption for the StormForce protocol.  I'm also looking into the XMPP protocol which may lead to another supported protocol...

---

7th October 2008 - News...
  * Sorry for the lack of updates recently, I've been very busy with other commitments.  Don't worry I haven't forgotten StormForce!

---

7th September 2008 - Re-released v0.5.3!!!
  * Forget to include the new font used in this version.

---

6th September 2008 - StormForce v0.5.3 released!
  * Here it is, at last!  This version now supports the Boltek StormTracker.  Don't forget to read all the README files.  Please note that there have been some changes to the settings XML file, some settings won't be upgraded so run StormForce once, close it, and change the relevant settings and reload StormForce - this is due to the StormTracker support since I had to create separate settings for both the LD-250 and the StormTracker.
  * Also, this version includes improved installation instructions for Linux.
  * You might not know this but StormForce now works with multicast, which means StormForce now supports TCP, UDP, and multicast.
  * As always let me know if you have any problems with this release!  (NOTE: compression on the protocol is still under development but you still can enable it if you want to test).

---

31st August 2008 - Upcoming release: v0.5.3
  * The StormTracker PCI driver is nearing completion, bear with me!  It will work either on the same machine as the StormTracker or via the network, useful if the machine is far away.  StormForce will (of course) share it via it's XML protocol if configured.

---

10th August 2008 - Upcoming release: v0.5.3
  * The next version will be backwards compatible with older versions of StormForce for its networking protocol and will be able to individually chose the devices you want.  This means (for example) that you can have your LD-250 being read from a local serial port, the EFM-100 from a remote location (either by a plain text protocol or XML if from StormForce) and so on.
  * Also the information panel has been changed to compensate for all the devices it now supports - LD-250, StormTracker (still finishing the driver), EFM-100, and GPS.
  * TRAC will also give you a bit more information in it's own panel.

---

7th August 2008 - StormForce v0.5.2 re-released!!!
  * Whoops!  Found a small problem where the server mode image never got created (didn't move all the options from the "old style" to XML correctly).  Re-released with the problem fixed.

---

6th August 2008 - StormForce v0.5.2 released!
  * Here is the next version of StormForce that now uses XML for it's settings and network protocol.  This will be the last time you'll have to use the "-h" option for the new features (you'll need to use the "-x" option along with your existing arguments to upgrade to XML).  As always, let me know if you find any bugs!

---

5th August 2008
  * There now appears to be Linux driver for the Boltek StormTracker (PCI).  I've currently obtained one of these and am working to see if I get it working with StormForce!  Watch this space!  (Hmmm... Looks like I've got to brush up on my C programming, it's been a while...)
  * The upcoming release is also nearing completion with the XML changes.  Again, watch this space!

---

31st July 2008 - Upcoming release: v0.5.2
  * Just a heads-up for you all.  The upcoming release will also be using XML for it's settings and also for it's networking protocol.  Don't worry, you'll be able to upgrade your settings to XML using this release.  However, older clients will not be able to connect until you update them too.  This will make it easier for third party applications to use the data sent from a StormForce server.  This might take a while so bare with me!

---

23rd July 2008 - Upcoming release: v0.5.2
  * Had another think about the uploading... It didn't work well it we wanted to upload the TRAC report as well.  So the next release will include support for uploading the TRAC report as well as the lightning image.  Watch this space!
  * I've also been thinking about adding a GUI to StormForce using wxPython.  This will certainly improve user experience and will allow more options than the command line can take!  Implementing this will take time and will slowly improve until we reach v1.0.0.  We'll get there eventually!

---

12th July 2008 - StormForce v0.5.1 released!
  * Here is the next release which includes support for uploading the lightning image to your website!  As always read the README for details.  The README file also contains improved installation instructions for FreeBSD and Microsoft Windows.  This release also contains a few bug fixes and tweaks that affect strike plotting.  Another feature in this release is that external programs can now be fired when the LD-250 alarms are set off.  Don't forget to use the "-h" flag for the new options!
  * Microsoft Windows users will need to download WinRAR to extract StormForce and will have to use WordPad (or NotePad++ if you have it) to read the README file.

---

8th July 2008 - Microsoft Windows SUPPORTED!
  * It appears StormForce works 100% under MS Windows!  The packages I installed were "python-2.5.2.msi", "pygame-1.8.0.win32-py2.5.msi", "Numeric-24.2.win32-py2.5.exe", "pywin32-211.win32-py2.5.exe", "pyserial-2.4.win32.exe", and "MySQL-python-1.2.2.win32-py2.5.exe".  Full instructions will be in the next release for those who want to wait.  If you don't want to wait, download the packages (from the appropriate website) and install, then add "C:\Python25" into your environment PATH and run StormForce via the command prompt.  Every feature appears to work correctly.  I'll try to get some screenshots up for you all!

---

2nd July 2008 - General Update
  * I haven't had much time for any development for StormForce recently.  However, I have implemented image uploading so you can put the lightning image onto your website!  This feature will require the binary of CURL when released.
  * If there are any Microsoft Windows users out there who can test StormForce on Windows for me, I would be grateful if you let me know how well it works.  Please raise any problems using the "Issues" link at the top (as far as I know all the packages (modules) I use should work in Windows, see the README file for the packages).  Thanks!

---

6th June 2008 - StormForce v0.5.0 released!
  * Finally, it's now ready for release.  As always, use "-h" option to set the new options/changes mentioned earlier.  Don't forget to read the README file as well.

---

2nd June 2008 - Another (!) update on upcoming release: v0.5.0
  * I think I've now done everything I wanted for this version, just needs some more testing!  Expect a general release sometime this week (likely to be the weekend)!

---

26th May 2008 - Another update on upcoming release: v0.5.0
  * The next version is nearing completion!  This version also includes support for a GPS device (RS-232 of course) and can also read the Boltek EFM-100 so you can monitor the electric field level.  Just need to complete a few things with TRAC first then I can release it.  Bare with me!

---

10th May 2008 - Update on upcoming release: v0.5.0
  * Managed to fix the locking problems with SQLite by implementing a locking system.  This does mean there is a decrease in performance but shouldn't be noticeable during normal plotting (but it is noticeable when using the "circle" feature in demo mode).  When this version is released you MUST provide the "-a" option to define the database engine you want to use (as always, check the arguments by passing "-h" to find out what is needed for your setup).  For the CSV users, there is now an option to import your CSV data into the SQL database.
  * For those of you who don't know what to do with the tarball on the download page, try this by opening up a console: "bzip2 -d stormforce-X.X.X.tar.bz2 && tar xf stormforce-X.X.X.tar" (change the X's with the version you downloaded) or if you're in KDE, Gnome, etc just try opening the file and extracting the "stormforce" folder to somewhere useful using the default extracter (usually Ark in KDE).

---

4th May 2008 - Upcoming release: v0.5.0
  * v0.5.0 will be released soon with improved TRAC (~250% faster) and MySQL/SQLite database support.  Please note that CSV support has been dropped.  I recommend to use MySQL v5.X since SQL views are needed and offers multiple database engines. I'm currently having a few locking problems with SQLite which I hope to get fixed soon.  Watch this space!

---

19th April 2008 - StormForce v0.4.4 released!
  * v0.4.4 has improved TRAC and debugging.  Check the README for more information.

---

14th April 2008 - StormForce v0.4.3 released!
  * v0.4.3 is my first release of StormForce onto the internet.

---


---
