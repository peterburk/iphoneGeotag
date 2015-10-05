# iPhone Geotag

<img class="aligncenter" alt="iPhone Geotag Logo" src="https://raw.githubusercontent.com/peterburk/iphoneGeotag/master/Icons/iPhoneGeotagIcon.png" width="128">

iPhone Geotag uses the iPhone location to tag Places for your photos in iPhoto and Aperture. It uses AppleScript, Apple’s high-level API into every Mac application.

Download it here: 
https://raw.githubusercontent.com/peterburk/iphoneGeotag/master/iPhoneGeotag.zip


iPhoneGE uses the iPhone location to make a Google Earth map. It is the first freely-available program of this kind compatible with iOS 3.

https://raw.githubusercontent.com/peterburk/iphoneGeotag/master/iPhoneGE.zip




Updates
- Now compatible with Aperture! It will tag photos in either iPhoto or Aperture, depending which is open. If both are open, it will tag in both!
- Now compatible with iOS 3! Select your hcells.plist in the choose file dialog.

• If you have a bug, please email me! I also have some reduced versions of the script that only work on the selection, and don’t delete the CSV. 
If you want to debug it yourself, get the one for iPhoto: 
https://raw.githubusercontent.com/peterburk/iphoneGeotag/master/MinimaliPhoto.zip 
or Aperture: 
https://raw.githubusercontent.com/peterburk/iphoneGeotag/master/MinimalAperture.zip

##About
The latest Apple scandal to hit the news was iPhoneTracker (https://petewarden.github.io/iPhoneTracker/). It turns out that the iPhone backup file stores a record of everywhere you’ve travelled since upgrading to iOS 4. Some panicked. Others argued. I was inspired to code.

##Usage
To run it, simply double click on the icon. If they’re not already, it will ask whether to tag in iPhoto and/or Aperture. If it can’t find your location data file, it will display a “Choose file” dialog. Then, it will display an alert with estimated runtime (about 10 mins). When completed, it will display another alert with some statistics: how many photos tagged, and total runtime.

##FAQ
- For iPhoto, please sort photos in ascending date order! (View > Sort Photos > By Date > Ascending). I tweaked the script to assume this to speed up runtime.
- Your location data is not transmitted to anywhere by using this script. It is kept on your computer at all times, do not fear!
- System requirements: iPhoto 8 or 9, iPhone with iOS 3 or 4
- On iOS 3, you’ll need to extract your hcells.plist file using DiskAid. Go to the iPhone’s root directory, then /Library/caches/locationd/cells.plist.
- This does not require an internet connection to run.
- The code is open-source, Apache 2.0. If you have any other ideas, feel free to copy subroutines from this!
- Hidden photos are not tagged by default. Use View > Hidden Photos to show them if you wish to tag these as well.
- You can increase runtime by changing the code to only tag selected photos.
- Glory to God for giving us this world to explore!
- Please email me with bug reports or further questions. I’d be happy to help!

