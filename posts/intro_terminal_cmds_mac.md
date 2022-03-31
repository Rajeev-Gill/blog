---
title: An Introduction to Using the Terminal on MacOS.
description: This is a post on My Blog about Bash commands within the MacOS terminal.
date: 2022-06-03
tags:
  - Tech
layout: layouts/post.njk
---
## Basic Commands

### Clear

```bash
$ clear = this clears the current window. (Within Terminal in OS X, you can still scroll up to see what was there. This command simply clears the current view
```

### Change Directory

```bash
$ cd /Applications/Utilities = You can navigate to a folder, such as Utilities, by typing the following command 'cd' to jump up a level
```
```bash
$ cd /Volumes/Macintosh\ HD/
$ cd "/Volumes/Macintosh HD/" = With folders that contain spaces, there’s two ways you can do it:
```

### List
```bash
$ ls = List the Contents of a Directory. To view it in a list format, enter: $ ls -l
```
```bash
$ ls = List the Contents of a Directory. To view it in a list format, enter: $ ls -l
```
```
$ ls -la = but also view all the hidden files?
```

### Server
```bash
$ python -m SimpleHTTPServer 8000 = to quickly test some HTML that you’re working on, start a simple web server within any folder on your Mac. Close with ctrl+c
```

### Download a file
```bash
$ curl -O http://appldnld.apple.com/iTunes11/091-6058.20130605.Cw321/iTunes11.0.4.dmg = download a file without using a browser
```

### Shutdown
```bash
$ sudo shutdown -h now = To shut down your Mac immediately
$ sudo shutdown -r now = To restart your Mac immediately
$ sudo shutdown -r +60 = We can even add a time delay (in minutes) if we wish
```

### Keep-awake
```bash
$ caffeinate = Prevent from sleeping, cancel with ctrl+c
$ caffeinate -u -t 600 = Prevent from sleeping, 600s (10m)
```

### Monitor a file
```bash
$ tail -f /var/log/system.log = constantly monitor your chosen file and display any new lines as they’re added, perfect for monitoring system log files
```