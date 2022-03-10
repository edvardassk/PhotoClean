# PhotoClean
Building AI course project

## Summary

Photo gallery in mobile phone quickly gets mix of everything: good and valuable photos of the family, travels, as well as "one day" photos like photos of clothes before making decision to buy them, prices of interesting item from shop, short term advertisments (e. g. to concert) and alike, which become not needed after a week, if not on the same day. To get rid of these not needed photos take determination: to go through and mark each to delete. Time consuming and uneffective. 
Idea: to label photos for deletion accoding to individual habints of mobile owner


## Background

Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?

Mobile phone photo galery cleaning from unneded photos is:
* time consuming
* repetitous 
* boring

If not cleaned it
* makes difficult to find actual, needed photos
* consumes phones memory intensivelly and I am asked from time to time clean photos otherwise phone performace slows down

Up to now mobile preinstalled software hadn't offered me solution for to make this manual job easier. In Google Play also nothing interesting was found. 

Actually quite common to see people saying that they have to clean photos before memory runs out.


## How is it used?

PhotoClean runs on mobile phone.
* regularly (a. g. monthly, weeekly, other metric, according to user set ups) PhotoClean runs through photo galery and labels photos: "Delete" and "Not_delete"
* list is showed to the mobile phone user as proposal for deletion of photos. Coul be like this
 ![Photos for deletion](/Screenshot_20220310-112031_Gallery.jpg)
* user can change the list either unmarking photos which are lableled "delete" by PhotoClean or adding others into deletion list
* user sends final deletion list to recycle bid
* PhotoClean analyses deletion preferences to improve for the next time
* after period set by user, process runs again

No code presented, as still in begginer level of courses


## Data sources and AI methods

Data naturally, is already in mobile phone photo gallery. 
ML is needed to analyse photos, and label then into "Delete" and "Not_delete". First analysis could be done after notification to phone user to mark certain numbers of photos user would like to delete. 
PhotoClean could be pretrained even before to recognize common patterns of photos to be labeled as "Delete". Initial accuracy would be very low: and photo taking and use of photos are very subjective and could be many clients segments. However ML should be able to adapt to individual client preferences with a time. 


## Challenges

At this stage PhotoClean does not add other labels to photos (e. g. like already available solutions which can recognize faces and label names accordingly). However possible to think about such extention in future
PhotoClean should follow Gallery ethical standarts set by producer (e. g. do not interrupt with abuse photos filterring used by Apple)

## What next?

To check, whether really this kind solution is not available yet. Maybe my search was simply not hard enough.
Find others interested in idea
Make feasibility study or dicussion
Proceed further depending on findings
