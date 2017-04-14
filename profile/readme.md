# Teacher Profile ![Build Status](http://devtools1.risevision.com:8080/job/Storage-Client-BranchPush/badge/icon)

## Introduction

The Teacher Profile Template was created to recognize a teacher by showing a short bio and image that would be typical of a school enviroment. A preview of the template can be seen here: http://commondatastorage.googleapis.com/risemedialibrary-395c64e5-2930-460b-881e-009aabb157df/content-templates/teacher-profile/teacher-profile.html

##Steps to run the Teacher Profile Template:##

1. Fork or download the entire content-templates repository.  
![alt tag](images/readme-step1.jpg)

2. Modify the files within the teacher-profile folder directory to fit your needs (see below on how to modify specific elements).  
![alt tag](images/readme-step2.jpg)

3. Host the entire “teacher-profile” folder directory in rise vision storage or your web hosting service.  
![alt tag](images/readme-step3.jpg)

4. Copy the link to the teacher-profile.html file where you have it hosted and insert the url into a schedule. (you can also add this link to the url gadget within a presentation)  
![alt tag](images/readme-step4.jpg)


##Directions to modify the Teacher Profile Template:##

####Changing the background image
Open teacher-profile.html, locate the following code and modify the src url of the img tag to the path of your new background:

```
<div class="swirl fade-in three">
    <img src="images/swirl.svg">
</div>
```
 
####Changing The Teacher Profile Text
Open teacher-profile.html, the text items are orgainzed within the following div tag ```<div class="text-container fade-in two">```.
Modify the text within the paragraph tags to meet your needs. 

The style is controlled within teacher-profile.css. There are 4 different media queries within the css used to control the font sizes. One for 1280x850, 1360x768, 1920x1080 and 3840x2160 which are the common display resolutions we see in digital sigange.

####Teacher Icon Graphic
Open teacher-profile.css, locate the ```.icon``` class and modify the   ```background: url(images/avatar-guy-beard.svg);``` to reflect the path of your new image.

The bouncing animation is built with css keyframes. To modify locate the following comment ```/* Teacher Profile Icon Animation */```. 

The size of the icon and shadow can be changed by modifying the
```.icon``` & ```.icon-shadow``` classes. 

The speed and iteration count of the animations can be changed by modifying the
```.icon-container``` class. 
 
## Built With
actual tools used
- HTML
- CSS

Teacher Profile Template works in conjunction with [Rise Vision](http://www.risevision.com), the [digital signage management application](http://rva.risevision.com/) that runs on [Google Cloud](https://cloud.google.com).

At this time Chrome is the only browser that this project and Rise Vision supports.

## Submitting Issues
If you encounter problems or find defects we really want to hear about them. If you could take the time to add them as issues to this Repository it would be most appreciated. Please Identify the specific template that has the issue and follow the following format where applicable:

**Reproduction Steps**

1. did this
2. then that
3. followed by this (screenshots / video captures always help)

**Expected Results**

What you expected to happen.

**Actual Results**

What actually happened. (screenshots / video captures always help)

## Contributing
All contributions are greatly appreciated and welcome! If you would first like to sound out your contribution ideas please post your thoughts to our [community](http://community.risevision.com), otherwise submit a pull request and we will do our best to incorporate it.

### Suggested Contributions
- Alternative ways to animate background
- Alternative ways to animate and transition between multiple teachers
- Dynamically update teacher profile from custom data source like google spreadsheeets
- i18n Language Support

## Resources
If you have any questions or problems please don't hesitate to join our lively and responsive community at http://community.risevision.com.

If you are looking for user documentation on Rise Vision please see http://www.risevision.com/help/users/

If you would like more information on developing applications for Rise Vision please visit http://www.risevision.com/help/developers/.

 If you have any questions or problems please don't hesitate to join our lively and responsive community at http://community.risevision.com.
 
**Additional Content Templates can be found here: https://github.com/Rise-Vision/content-templates**

**Facilitator**

[Mathew Meiers](https://github.com/mmeiers "Mathew Meiers")
