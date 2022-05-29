---
layout: post
title: "Introduction to Scorefold"
author: "Lukas"
---

# Introduction to Scorefold

This should give some insight into the problems I want to solve with Scorefold.

## About me

I am Lukas Plechinger, a software developer from Graz, Austria. I play the drums in a wedding/event band 
and try to develop an app (called Scorefold) to solve some of the problems I encounter on a lot of gigs with my band.

## The problem(s)
I play the drums in an event and wedding band. We all use tablets like an iPad to
view our sheet music during a gig and for the distribution we use software like 
Dropbox and GDrive. 

This is far from a perfect solution. Even after years of playing with the same
people, we still encouter the following problems:

 - Somebody forgot to download the sheets for a new song, but there is no internet availability at the venue.
   (Couples seem to love remote locations for their wedding)
 - Our bandleader gives a cue, but some band members don't get it and need to search for the correct sheet.
 - Due to the lack of consistency, I sometimes forgot the filename a song is stored with and can not find it. 
   Not a big deal for our singers, but as a drummer I usually have to play for the entirety of a song and can't search for the sheet while playing
 - The keyboarder/guitarist is still setting up a special instrument patch for a song

During a gig, all those situations can cause a lot of stress and long pauses between the songs. 
Those pauses are always very awkward and in the worst case, guests use the pause to grab a drink and leave
the dancefloor.

## The solution

Almost immediately after I started with the band in 2017, I wanted to develop an app which tries to solve those problems.
Due to several interruptions, too little spare time and many other factors, development never really kicked off until march 2022.

Now I am committed to release a basic version of the app by the end of summer 2022. This devlog will document the progress and give you a glimpse of the features I am working on.

## Planned features

This is a list of the features I want to implement in the app. The first release will include all the MVP features, the other features are ideas and "nice to have" features for the future.
If you are interested in a particular feature, send me a message - I would love to talk about it.

**MVP features**

 - Manage songs and several sheets per song (e.g. one for each instrument)
 - Add additional info to the song: recommended bpm, key, etc.
 - "offline first" - approach: If you view a sheet once, it will be available the next time, even without internet.
 - Upload the song library for a band
 - Share the song library with the other members of your band
 - Automatically synchronize the song library
 - Ability to manage multiple bands

*Planned features*

 - Add custom notes to a sheet
 - "Live Mode" - all members of the band get notified when the bandleader opens a song
 - Store MIDI commands: Change the instrument patch, start backing tracks, start a light show etc.
 - React to MIDI commands: scroll on command (e.g. by using a foot switch)

## Outlook

In this blog I will try to give weekly updates to the progress of the app development. Stay tuned.
