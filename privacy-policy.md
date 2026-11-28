# Iqal — Privacy Policy

*Last updated: 23 November 2026*

Iqal is a free, open-source website and app blocker for Windows and Linux. This policy covers the Iqal app and the Iqal browser extension.

## What Iqal handles

To decide whether something is blocked, Iqal looks at:

- **the address of each web page** you open (by the browser extension);
- **which page is in front of you**, every 15 seconds (by the browser extension), to count time for daily allowances you set;
- **the names of websites** your computer looks up, and **the programs and window titles** that run on it (by the Iqal app);
- **the Wi-Fi networks in range**, only while you use a "while at a place" lock.

## Where it goes

All of this is handled **on your own computer**. The extension passes page addresses only to the Iqal app installed on the same computer, which compares them with the blocks you created.

- Nothing is sent to the developer.
- Nothing is sent to any other company or server.
- There is no account, no analytics, no advertising and no tracking.

Iqal connects to the internet for these purposes only:

- **Time checks:** asking public time servers for the correct time, so locks cannot be shortened by changing the clock. Only the time request is sent.
- **List updates:** downloading updates of the ready-made block lists from their public sources.
- **Location look-ups:** if you use a "while at a place" lock and Windows/Linux location services are on, the operating system's own location service may look up nearby Wi-Fi networks. Iqal itself sends nothing.

## Iqal for Android

The Android app works the same way: your blocks stay on your phone, and nothing
is sent to the developer. Iqal keeps a record of its own checks for 72 hours
(Settings → Check log), so problems can be found; it leaves the phone only if
you copy or share it yourself. On the phone it uses:

- **the list of installed apps** and **Android's usage records**, to switch
  apps off and to count time for daily allowances;
- **the phone's position (GPS)**, only while you use a "while at a place" lock,
  read on the phone through Android's own location service. On phones with
  Google Play services, Google's place watch tells Iqal when you arrive at or
  leave the place: for this, the place's position is given to Google Play
  services on the phone, under
  [Google's privacy policy](https://policies.google.com/privacy);
- **Chrome settings**: the blocked websites go into Chrome's own block list.
  When "Block adult content" is on, Chrome looks up website names through
  CleanBrowsing's family filter (`doh.cleanbrowsing.org`), which refuses adult
  sites. CleanBrowsing then sees which website names are looked up, under
  [its own privacy policy](https://cleanbrowsing.org/privacy).
- **the map** for a "while at a place" lock: its pictures come from
  OpenStreetMap. To send them, OpenStreetMap's servers see your internet
  address and which area of the map you look at, under
  [their own privacy policy](https://osmfoundation.org/wiki/Privacy_Policy).
  The pictures are kept on the phone, so an area loads only once a month.

## Your choices

You decide what is blocked, and you can see, change or delete your blocks in the Iqal app. Uninstalling Iqal removes the extension and the programs. On Linux, `apt purge iqal` also deletes your blocks; on Windows they are kept in `C:\ProgramData\Iqal`, in case you install Iqal again, until you delete that folder. (A block that is locked keeps Iqal installed until its lock ends; that is what a lock is for.)

## Contact

Questions about this policy: zakaria1adam1@gmail.com
