# MonitoringProject
Final Project of Monitoring Technological Development
Group #2


 
**Fading ActionBar:**
Fading Action Bar is a library which implements the cool fading action bar effect that can be seen in the new Play Music app.
This library uses the techniques outlined by Cyril Mottier in a recent blog post.
The way this effect is achieved is by effectively setting the alpha level of Action Bar Drawable from maximum to zero as we scroll up and down. In order to achieve this effect, we need to know when the scroll state of the Scroll View has changed. This might seem like a trivial task, but thanks to Android not implementing an accessible event, we must create a workaround. To do this, we will extend the existing Scroll View and make it fire an event. In order to stay consistent with the original post, we will call it Notifying Scroll View . Then we will add an event handler which takes our Notifying Scroll View and the context of the calling Activity and and handles the fading for us.
 
![image](https://user-images.githubusercontent.com/39096188/48374779-ddc42380-e693-11e8-833b-dba5753e3b4e.png)






**STEP 1: CREATED ANDROIDMANIFEST.XML FILE:**
 

**Step 2: Created activity_main.xml file for layout or Design of an application.**
 
**Step 3: Created activity_profile.xml file**
 

**Step 4: Created activity_scrolling.xml file**
 
 



**Step 5: Created content_profile.xml file**
 
 
**Step 6: Created content_scrolling.xml file**
 
**Step 7: Created customview.xml file**
 
 

**Step 8: Created menu_scrolling.xml file**

 

**Step 9: Created MainActivity.java file**
 

**Step 10: Created List.java file**

 
 
**Step 11: Created Profile_activity.java file**
 
**Step 12: Created Scrolling_activity.java file**

 
 

**App Screenshots:**
 
 

 
References:
https://stackoverflow.com/questions/30846265/how-to-center-the-title-of-a-collapsingtoolbarlayout?fbclid=IwAR1ZgglA5yRqHitFt4W8jdXAmPg3U13fHUfMY1cv0q_hIpwhUi1SRVcdgd8
https://stackoverflow.com/questions/31662416/show-collapsingtoolbarlayout-title-only-when-collapsed?fbclid=IwAR3H7a4Wfk7TTsvTAnAAaqBqBzEGa8k2BTqes5mZu4M4PvFQjXgJL1BlwMY
https://www.journaldev.com/13927/android-collapsingtoolbarlayout-example?fbclid=IwAR2kMQK_MwAHSzinI9tTgeca9CZeR-IHJkzw7Bb9yfNFXxaQXvhATR7AHrI
https://www.youtube.com/watch?v=NZ9DJLBKmno&fbclid=IwAR1UyCqZ0FUzP4QmNdeBnIO-XWuki85HGE4jdDSEYZ5ITu0qvL6WsjkI6L4

