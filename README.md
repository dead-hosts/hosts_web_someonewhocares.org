# About hosts_web_someonewhocares.org

[![Build Status](https://travis-ci.org/dead-hosts/hosts_web_someonewhocares.org.svg?branch=master)](https://travis-ci.org/dead-hosts/hosts_web_someonewhocares.org)

```
# This hosts file is brought to you by Dan Pollock and can be found at
# <A HREF="http://someonewhocares.org/hosts/zero/">http://someonewhocares.org/hosts/zero/</A>
# You are free to copy and distribute this file for non-commercial uses,
# as long the original URL and attribution is included.
#
# See below for acknowledgements.

# Please forward any additions, corrections or comments by email to
# hosts@someonewhocares.org

# Use this file to prevent your computer from connecting to selected
# internet hosts. This is an easy and effective way to protect you from
# many types of spyware, reduces bandwidth use, blocks certain pop-up
# traps, prevents user tracking by way of "web bugs" embedded in spam,
# provides partial protection to IE from certain web-based exploits and
# blocks most advertising you would otherwise be subjected to on the
# internet.

# There is a version of this file that uses 127.0.0.1 instead of 0.0.0.0
# available at <A HREF="http://someonewhocares.org/hosts/">http://someonewhocares.org/hosts/</A>.
# On some machines this may run minutely faster, however the zero version
# may not be compatible with all systems.

# This file must be saved as a text file with no extension. (This means
# that the file name should be exactly as below, without a ".txt" appended.)

# Let me repeat, the file should be named "hosts" NOT "hosts.txt".

# For Windows 9x and ME place this file at "C:\Windows\hosts"
# For NT, Win2K and XP use "C:\windows\system32\drivers\etc\hosts"
#                       or "C:\winnt\system32\drivers\etc\hosts"
# For Windows 7 and Vista use "C:\windows\system32\drivers\etc\hosts"
#			or "%systemroot%\system32\drivers\etc\hosts"
# For Windows 8 and Windows 10 use "C:\Windows\System32\drivers\etc\hosts"
# 		You may need to tell Windows Defender to ignore this path
# 		see: http://support.microsoft.com/kb/2764944
# You may have to use Notepad and "Run as Administrator"
#
# For Linux, Unix, or OS X place this file at "/etc/hosts" or on some
#    systems at "/private/etc/hosts". You will require root access to do
#    this. Saving this file to "~/hosts" will allow you to run something
#    like "sudo cp ~/hosts /etc/hosts".
# For OS/2 copy the file to "%ETC%\HOSTS" and in the CONFIG.SYS file,
#    ensure that the line "SET USE_HOSTS_FIRST=1" is included.
# For BeOS place it at "/boot/beos/etc/hosts"
# On a Netware system, the location is System\etc\hosts"
# For Macintosh (pre OS X) place it in the Mac System Folder or Preferences
#    folder and reboot. (something like HD:System Folder:Preferences:Hosts)
#    Alternatively you can save it elsewhere on your machine, then go to the
#    TCP/IP control panel and click on "Select hosts file" to read it in.
#    ------------------
#    | As well, note that the format is different on old macs, so
#    | please visit <A HREF="http://someonewhocares.org/hosts/zero/mac/">http://someonewhocares.org/hosts/zero/mac/</A> for mac format
# For Android place the file at "/system/etc/hosts". You will need root
#   access on your device to do this.
#    ------------------
# To convert the hosts file to a set of Cisco IOS commands for Cisco routers
#   use this script by Jesse Baird:
#   <A HREF="http://jebaird.com/blog/hosts-ip-host-generating-blocked-hosts-host-file-cisco-router">http://jebaird.com/blog/hosts-ip-host-generating-blocked-hosts-host-file-cisco-router</A>

# If there is a domain name you would rather never see, simply add a line
# that reads "0.0.0.0 machine.domain.tld". This will have the effect of
# redirecting any requests to that host to your own computer. For example
# this will prevent your browser from downloading banner ads, or sending
# your information back to a company.
```

--------------------------------------------------------------------------------

# About Dead-hosts

[Dead-Hosts](https://github.com/dead-hosts) is the replacement of the original idea behind [funilrys/dead-hosts](https://github.com/funilrys/dead-hosts).
Indeed, the idea was to test - with the help of PyFunceble and Travis CI - hosts file, list of domains or even bocklist to have a list of only active domains or IP.

Today, we provide our infrastructure for anybody who want it. [Just ask](https://github.com/dead-hosts/dev-center/issues/new?template=inclusion-request.md)!

--------------------------------------------------------------------------------

# About PyFunceble

PyFunceble is the tool that our infrastructure use to get the status (ACTIVE, INVALID, INACTIVE) of a given domain or IPv4.

Please find more information about it there:

* http://pyfunceble.github.io
* http://pyfunceble.readthedocs.io
* https://github.com/funilrys/PyFunceble

