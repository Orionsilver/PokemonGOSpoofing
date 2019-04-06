# Welcome to the Pokemon GO Spoofing guide #


* [Unrooted Devices](#Unrooted_Devices)
   * [How to Downgrade Google Play Services](#Downgrade_GP_Services)
   * [How to STOP Google Play Updates](#Stop_GP_Services_Updates)
* [Rooted Devices](#Rooted_Devices)
   * [How to hide root](#How_to_hide_root)

<h1 id="Unrooted_Devices">Unrooted Devices</h1>
<h2 id="Downgrade_GP_Services">How to downgrade Google Play Services</2>
<h3>Recently Niantic made some changes which require non root users to update their Google Play services Version. So if you're affected by it you'll need to update your Google Play Services version</h3>

The version that will work on your phone is unknown but there's a few versions that you can try and stick with the one that works for you. Those are [12.5.29](https://www.apkmirror.com/apk/google-inc/google-play-services/google-play-services-12-5-29-release/) , [12.6.85](https://www.apkmirror.com/apk/google-inc/google-play-services/google-play-services-12-6-85-release/), [12.6.87](https://www.apkmirror.com/apk/google-inc/google-play-services/google-play-services-12-6-87-release/) and [12.6.88](https://www.apkmirror.com/apk/google-inc/google-play-services/google-play-services-12-6-88-release/). Before you downgrade do the following go to **Settings -> Device Administrator -> _UNCHECK_ "Find My Device"**. Afterwards proceed to install any version mentioned above and **reboot your phone** then check if you're able to spoof.

### How to know the right version for your phone ###

The easiest way is to go to Settings -> Apps -> All Apps -> Google Play Services which will bring you to this screen:

<img src="images/GooglePlayServices.png"/>

In this example we can see my current Google Play Services Version: **16.0.89**. Followed by **(040408-...)** 

Those **040408** numbers are the ones we want to find out the version for our phone. Obviously your phone can/will have different ones but reffer to this as an example.

So let's pretend we want to download the version **12.6.85** (linked above) for my phone. We can see there's many **Variants** on apkmirror.com _What a mess!_ You just go on your browser and press **CTRL-F** (⌘ Cmd+F if you're on mac) and type the _magic numbers_ **040408** in my case it found this result:

<img src="images/googleplayservices1.PNG" alt="hi" class="inline"/>

Then proceed to download and install it accordingly.
<h2 id="Stop_GP_Services_Updates">How to Stop Google Play Updates</h2>
<p>This is a necessary step for non-root users so you don't have to downgrade all the time because Google Play Services updates itself on the background. So let's start off by Disabling mobile background data for Google Play Services:</p>
1. Start by going to your phone's Settings
2. Click on "Apps" <br>
<img src="images/stop_gp_updates_1.png">
3. Click on "Google Play Services <br>
<img src="images/stop_gp_updates_2.png">
4. Click on **Mobile Data** Note: In some phones it's called **Data Usage**
<img src="images/stop_gp_updates_3.png">
5. Disable any background data permissions the app has. (Some devices will have different names for the option. Just untoggle all the Data permissions)
<img src="images/stop_gp_updates_4.png">
6. If you need to downgrade your Google Play Services do it now. Reffer to <a href="#how-to-downgrade-google-play-services">How to Downgrade Google Play Services</a>

7. Next we want to Disable Google Play Services storage permissions. (Reffer to the picture on the Step 4) and Click on **Permissions**
<img src="images/stop_gp_updates_5.png">
8. Then untoggle **Storage**
<img src="images/stop_gp_updates_6.png">

<h1 id="Rooted_Devices">Rooted Devices</h1>

<h2 id="How_to_hide_root">How to properly hide root from Pokemon GO</h2>
<h3> Hiding root from Pokemon GO is fairly simple </h3>

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
<p>That's it! Pokemon GO shouldn't detect root anymore. Open it and test. If you do happen to get invalid OS error then check in your internal storage and delete any folder(s) with the name <b>"Magisk"</b>, <b>"Magisk Manager"</b> and retry to open Pokemon GO</p>
