# MonitoringProject

Final Project of Monitoring Technological Development

Group  2 

 Team Members: Akashdeep Sharma(1794147), Madhuri Patel(1794882), Gaurav Shepla(1794331), Baljeet Singh(1793897) 

**Fading ActionBar:**

Fading Action Bar is a library which implements the cool fading action bar effect that can be seen in the new Play Music app.
This library uses the techniques outlined by Cyril Mottier in a recent blog post.
The way this effect is achieved is by effectively setting the alpha level of Action Bar Drawable from maximum to zero as we scroll up and down. In order to achieve this effect, we need to know when the scroll state of the Scroll View has changed. This might seem like a trivial task, but thanks to Android not implementing an accessible event, we must create a workaround. To do this, we will extend the existing Scroll View and make it fire an event. In order to stay consistent with the original post, we will call it Notifying Scroll View . Then we will add an event handler which takes our Notifying Scroll View and the context of the calling Activity and and handles the fading for us.
 
![image](https://user-images.githubusercontent.com/39096188/48374779-ddc42380-e693-11e8-833b-dba5753e3b4e.png)






**STEP 1: CREATED ANDROIDMANIFEST.XML FILE:**

 ![image](https://user-images.githubusercontent.com/39096188/48374871-0f3cef00-e694-11e8-8b32-4e75755585dd.png)

**Step 2: Created activity_main.xml file for layout or Design of an application.**

 ![image](https://user-images.githubusercontent.com/39096188/48374905-27ad0980-e694-11e8-813c-89c0f181dc11.png)

**Step 3: Created activity_profile.xml file**

 ![image](https://user-images.githubusercontent.com/39096188/48374927-37c4e900-e694-11e8-8b7a-1e08d69db216.png)

**Step 4: Created activity_scrolling.xml file**
 
![image](https://user-images.githubusercontent.com/39096188/48374980-60e57980-e694-11e8-9799-8f096bf60bff.png)

![image](https://user-images.githubusercontent.com/39096188/48375000-6fcc2c00-e694-11e8-83ab-a33c81c98cfc.png)

**Step 5: Created content_profile.xml file**

 ![image](https://user-images.githubusercontent.com/39096188/48375017-7ce91b00-e694-11e8-9913-3a922096073a.png)
 
 ![image](https://user-images.githubusercontent.com/39096188/48375152-04368e80-e695-11e8-83ea-84502beaa20f.png)
 
**Step 6: Created content_scrolling.xml file**
 
 ![image](https://user-images.githubusercontent.com/39096188/48375161-10bae700-e695-11e8-9e18-e2496e485e3d.png)
 
**Step 7: Created customview.xml file**
 
 ![image](https://user-images.githubusercontent.com/39096188/48375183-1dd7d600-e695-11e8-8844-d8026ba7879c.png)
 
 
![image](https://user-images.githubusercontent.com/39096188/48375194-29c39800-e695-11e8-994d-bc74b7a587d8.png)

**Step 8: Created menu_scrolling.xml file**

 ![image](https://user-images.githubusercontent.com/39096188/48375207-3647f080-e695-11e8-826c-90851d87a511.png)

**Step 9: Created MainActivity.java file**


![image](https://user-images.githubusercontent.com/39096188/48375219-3f38c200-e695-11e8-90ca-f9522fcb9d80.png)

**Step 10: Created List.java file**

 ![image](https://user-images.githubusercontent.com/39096188/48375230-495ac080-e695-11e8-9f39-e3a0fdba75c1.png)
 
 

![image](https://user-images.githubusercontent.com/39096188/48375244-55df1900-e695-11e8-9588-ecbc22c813ad.png)

 
**Step 11: Created Profile_activity.java file**
 
 ![image](https://user-images.githubusercontent.com/39096188/48375258-61324480-e695-11e8-86b1-2576fb5aedc2.png)

 
**Step 12: Created Scrolling_activity.java file**

![image](https://user-images.githubusercontent.com/39096188/48375270-6c857000-e695-11e8-84a3-dbf041c34140.png)
 
 ![image](https://user-images.githubusercontent.com/39096188/48375281-78713200-e695-11e8-994f-0b217305ef33.png)

**App Screenshots:**
 
 ![image](https://user-images.githubusercontent.com/39096188/48375303-83c45d80-e695-11e8-968c-555647506503.png)

 
![image](https://user-images.githubusercontent.com/39096188/48375319-8e7ef280-e695-11e8-9283-9764cea88e25.png)


![image](https://user-images.githubusercontent.com/39096188/48375331-98a0f100-e695-11e8-8c0a-52479de80bea.png)

**References:**

https://stackoverflow.com/questions/30846265/how-to-center-the-title-of-a-collapsingtoolbarlayout?fbclid=IwAR1ZgglA5yRqHitFt4W8jdXAmPg3U13fHUfMY1cv0q_hIpwhUi1SRVcdgd8
https://stackoverflow.com/questions/31662416/show-collapsingtoolbarlayout-title-only-when-collapsed?fbclid=IwAR3H7a4Wfk7TTsvTAnAAaqBqBzEGa8k2BTqes5mZu4M4PvFQjXgJL1BlwMY
https://www.journaldev.com/13927/android-collapsingtoolbarlayout-example?fbclid=IwAR2kMQK_MwAHSzinI9tTgeca9CZeR-IHJkzw7Bb9yfNFXxaQXvhATR7AHrI
https://www.youtube.com/watch?v=NZ9DJLBKmno&fbclid=IwAR1UyCqZ0FUzP4QmNdeBnIO-XWuki85HGE4jdDSEYZ5ITu0qvL6WsjkI6L4

