# Introduction

*   Today I will show you my gps Logger
*   This gps can be made for under 20 euros
*   And it pretty straightforward to use as there is only an on/off switch. 
*   When you power it up, the GPS will start to search for satellites for about 5 minutes
*   And then every 15gseconds, it will write your current position on a micro sd card
*   If you want to see how we made this GPS.
*   Watch the video in the description.
*   Let’s see what’s inside this case.

# Components

*   We have an arduino mini pro 3V
*   A microsd adapter
*   A gps with his antenna
*   A buzzer which will warm us if something doesn’t works
*   And finally a battery holder to power everything

Once you recorded a track on your microsd card you can display it on your computer using the website : gpsies.com or the software: viking

# Retrieve the GPS track

*   As an example we are going to use the track available in the documentation named : example.csv

## Text editor

*   First, Let’s open it with a text editor
*   As you can see the file is easy to understand and can be easily parse by others softwares
*   Let's see our track on a map and convert it as a gpx.

## Gpsies.com

*   The easiest way to do this, is to use the website gpsies.com
*   We just have to create a track and then import our file example.csv
*   We, now can see our gps track on a map
*   If you want to convert your track to read it with any GPS
*   Go to convert, browse, open your track
*   Click on Convert , and this will automatically download the gpx file

## Viking

*   You can also convert your track using the free software viking
*   Go to file, retrieve, import file with gps babel
*   Then open the csv file on the SD card of your GPSLogger
*   Finally go at the end of the list, to universal csv with field structure in first line
*   And press OK
*   This will display your track
*   You still need to add a map
*   We are going to use openstreetmap
*   You can use other maps like bing Aerial,
*   or even photos, scanned map…
*   The map will be download on your computer, so you won’t need a internet connection afterwhile
*   Click on OK
*   And that's it

# Ending

*   As always, all the link are in the description
*   Feel free to ask questions in the comments
*   And subscribe if you don’t want to miss my next projects!
*   Next time, we will see how to make a synth with a Raspberry Pi
*   Using samplerbox
*   I’ll try to make it as easy as possible
*   And show you my mod to use it as a drum machine
*   See you soon!

# Demo