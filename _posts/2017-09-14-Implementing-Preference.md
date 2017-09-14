---
title:  "Implementing Preference"
image: preference.png
tag: [Android, CodeCar]
---

### PreferenceActivity In Android

**PreferenceActivity**  is the base class for an activity to show a hierarchy of preferences to the user.
It is generally used for saving the setting/preference of  User. Android provides excellent framework to save and mange the User preferences.

In this I have created a Page/Screen with user can connect to CodeCar, change his password, and other choices/details.

Steps:

1: Create xml resource for Preference:  create an xml file inside xml folder (if xml folder is not there inside res folder, create xml folder inside res folder. In the example I have created user_settings.xml file inside xml folder.

2: Create a Class which extends PreferenceActivity class , and inflate the created xml using addPreferencesFromResource() method.

3: Call/Start the PreferenceActivity (created in 2nd steps) from where you want. In the example I have called from MainActivity using startActivityForResult()   method.

So lets check it out

![CodeCar Intro](/images/preference/3.png "CodeCar Preference"){: .img-responsive .thumbnail  .max-image-height}

And this is the Rest

![CodeCar Intro](/images/preference/4.png "CodeCar Preference"){: .img-responsive .thumbnail  .max-image-height}

**Note**: Rating currently is not working since CodeCar is not an official Play Store App.

![CodeCar Intro](/images/preference/5.png "CodeCar Preference"){: .img-responsive .thumbnail  .max-image-height}

If we head to the link section and press any link itll take us to the corresponding link to it
For example we pressed the Visit CodeCar Website

![CodeCar Intro](/images/preference/6.png "CodeCar Preference"){: .img-responsive .thumbnail  .max-image-height}

Preference also allow you to change password from within the activity

![CodeCar Intro](/images/preference/7.png "CodeCar Preference"){: .img-responsive .thumbnail  .max-image-height}

Contact Us for support or just sending feeback on your experience with CodeCar

![CodeCar Intro](/images/preference/8.png "CodeCar Preference"){: .img-responsive .thumbnail  .max-image-height}

Share CodeCar Website or App link (Currently only share the website link)

![CodeCar Intro](/images/preference/9.png "CodeCar Preference"){: .img-responsive .thumbnail  .max-image-height}

Send it to anyone you want using any app

![CodeCar Intro](/images/preference/10.jpg "CodeCar Preference"){: .img-responsive .thumbnail  .max-image-height}

Aslo if you having hard time or you just a begginer in coding you change the difficulty level while playing CodeCar

![CodeCar Intro](/images/preference/11.png "CodeCar Preference"){: .img-responsive .thumbnail  .max-image-height}

**Note**: CameraBackground allow you to make the wallpaper or the background of your app as a background to play while seeing your CodeCar or even while walking.


That's all for now, if you have any comment please tell us below.