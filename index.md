# Welcome to the Pokemon GO Spoofing guide #


[Unrooted Devices](#Unrooted_Devices)<br>
[Rooted Devices](#Rooted_Devices)

# The guide will need a lot of work and will be updated during my free time #

<h1 id="Unrooted_Devices">Unrooted Devices</h1>
<h3>Recently Niantic made some changes which require non root users to update their Google Play services Version. So if you're affected by it you'll need to update your Google Play Services version</h3>

The version that will work on your phone is unknown but there's a few versions that you can try and stick with the one that works for you. Those are [12.5.29](https://www.apkmirror.com/apk/google-inc/google-play-services/google-play-services-12-5-29-release/) , [12.6.85](https://www.apkmirror.com/apk/google-inc/google-play-services/google-play-services-12-6-85-release/), [12.6.87](https://www.apkmirror.com/apk/google-inc/google-play-services/google-play-services-12-6-87-release/) and [12.6.88](https://www.apkmirror.com/apk/google-inc/google-play-services/google-play-services-12-6-88-release/). Before you downgrade do the following go to **Settings -> Device Administrator -> _UNCHECK_ "Find My Device"**. Afterwards proceed to install any version mentioned above and **reboot your phone** then check if you're able to spoof.

### How to know the right version for your phone ###

The easiest way is to go to Settings -> Apps -> All Apps -> Google Play Services which will bring you to this screen:

<img src="images/GooglePlayServices.png"/>

In this example we can see my current Google Play Services Version: **16.0.89**. Followed by **(040408-...)** 

Those **040408** numbers are the ones we want to find out the version for our phone. Obviously your phone can/will have different ones but reffer to this as an example.

So let's pretend we want to download the version **12.6.85** (linked above) for my phone. We can see there's many **Variants** on apkmirror.com _What a mess!_ You just go on your browser and press **CTRL-F** (⌘ Cmd+F if you're on mac) and type the _magic numbers_ **040408** in my case it found this result:

<img src="googleplayservices1.PNG" alt="hi" class="inline"/>

Then proceed to download and install it accordingly.

<h1 id="Rooted_Devices">Rooted Devices</h1>

<h3>How to properly hide root from Pokemon GO</h3>
<h2> Hiding root from Pokemon GO is fairly simple </h2>

<p>Start by opening the Magisk Manager app and click on the highlighted button (picture below) </p>
<img src="images/magisk_manager.jpg"/>
<p>Then select Settings (picture below) </p>
<img src="images/magisk_settings.png"/>
<p>Then press "Hide Magisk Manager"(4th option) (picture below)</p>
<img src="images/magisk_manager1.jpg"/>
<p>Magisk should close in order to change the package name. You can check if it was sucessful by repeating the same steps and checking if now instead of **Hide Magisk Manager** it says **Restore Magisk Manager**. If it doesn't you'll have to repeat this step again. Otherwise continue on.</p>
<img src="images/magisk_manager2.jpg">
<p>Now click the top left corner button like you did on the first step since we started (first picture) and select **Magisk Hide**</p>
<img src="images/magisk_manager3.png"/>
<p>There you will find a list of your installed apps. Put a :white_check_mark: on Pokemon GO </p>
<img src="images/magisk_manager4.png"/>
<p>That's it! Pokemon GO shouldn't detect root anymore. Open it and test. If you do happen to get invalid OS error then check in your internal storage and delete any folder(s) with the name "Magisk", "Magisk Manager" and retry to open Pokemon GO</p>
