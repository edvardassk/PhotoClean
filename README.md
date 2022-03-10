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
*makes difficult to find actual, needed photos
*consumes phones memory intensivelly and I am asked from time to time clean photos

Up to now no of mobile preinstalled software offered me solution for this manual job. In Google Play also nothing interesting. 

Quite common to see people saying that they have to clean photos as mphones memory runs out


## How is it used?

*Regularly (a. g. monthly, weeekly, other metric, according to user wishes) PhotoClean runs through photo galery and labels photos: "delete" and "not delete"
*list is showed to the mobile phone user as proposal for deletion of not needed photos
*User can change the list either unmarking photos which are lableles "delete" or adding others into deletion list
*User sends final deletion list to recycle bid
*PhotoClean analyses deletion preferences to improve for the next time


Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Here are pictures of photos I would like to delete:

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods

Data naturally, is laready in mobile phone galery. 
ML is neede to analyse photos, which client prefers to delete. First analysis could be done ater notification to client to mark certain numbers of photos clients would like to delete. 
PhotoClean could be pretrained even before upload to recognize common patterns of photos to be labeled as deleted, but initial accuracy wiould be very low, as photo use is very 
subjective and could be many clients segments with differnet photo taking and photos use styles. However ML should be able to adapt to individual client preferences with a time. 

by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
