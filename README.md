Tutorial Persona 5 Phone Theme

# Requirements

- Apps
  - KLWP Pro
  - KWGT Pro
  - Nova Launcher
  - Persona 5 Widget
  - Persona 5 IM
  - MacroDroid (optional)
- Files
  - 4 Widgets
  - Icon Pack
  - Nova Launcher Backup
  - Themes
  - Sound File (optional)

# Downloads

1. Download Nova Launcher on the Play Store: <https://play.google.com/store/apps/details?id=com.teslacoilsw.launcher>
1. Download the Persona 5 Widget on the Play Store: <https://play.google.com/store/apps/details?id=blueberry.is.cool>
1. Download KLWP Pro, do this by downloading the APK on your phone and clicking on it.
1. Download KWGT Pro, see step 3.
1. Download MacroDroid on the Play Store: <https://play.google.com/store/apps/details?id=com.arlosoft.macrodroid>

That’s all you have to do know, I’ll get to the other files later.

# Nova Launcher Setup

If Nova Launcher is installed on your phone make sure it’s set as your default launcher.
For Samsung you do it this way: settings -> apps -> choose default apps -> home app -> select Nova Launcher

You can always go back by selecting your default launcher.
After you’ve done that download the Nova backup file which is named “Persona5LayoutNova.novabackup”. Then open Nova Settings on your phone, scroll till you find “Backup and import settings”. Click on it and tap restore backup, then search and use the backup you just downloaded.

Also make sure you have 3 screens or pages, you could have more but the animations might be odd. You can change this by long pressing the home screen, long press a page to delete it, click the plus sign to add one.

You can customize stuff in Nova but don’t turn off the setting “wallpaper scrolling”.

_For more info go here: [https://sites.google.com/jerieljan.com/p5-confidants/home_](https://sites.google.com/jerieljan.com/p5-confidants/home)\*

# KLWP Pro Setup

After you have installed KLWP Pro download the KLWP Persona theme from this site: <https://sites.google.com/jerieljan.com/p5-confidants/home>

You could choose the version you want but if you want it to be like mine or aren’t sure download version 1.3: Click on the “download” tab in the top right corner and then click “Download v1.3”. The file should be downloaded on your phone.

The reason you needed to _not very legally_ download the Pro version is because the normal version doesn’t support importing other themes. You could’ve also bought it on the Play Store if you wanted.

If you’re ready open the KWLP Pro app, tap on import in the top right corner and choose the file you downloaded from the site. The file should end with .kwlp.

You’ll find the theme under “wallpapers”, click on it and you can edit it. Click on the save icon on the top and accept everything the apps asks for, the “fitness permission” isn’t needed. Make sure set Kustom/KLWP as your live wallpaper for your home screen and also your lock screen if you want.

Customization: You can customize some stuff, go into the editor and in the bottom under items you can click on an item to change it position. You can also change the animation of the album items and location bar to make it stop moving when you shake your phone. Just disable “ReactOn”.
Do you want another *persona*ge in your theme? If yes go into the editor and click the “Globals” tab. You can change the number next to “cchoice” to choose the character you want.
Finally don’t forget to take a look at the Kustom LWP settings itself.

# KWGT Pro Setup

When you have KWGT Pro installed on your phone, download the “Widgets” folder. The reason you needed to download the Pro version is the same as for the KWLP app.

Import every widget you will use. You can choose if you want to use the Date/Weather widget in the widgets folder you downloaded or the one from the Persona 5 Widget from the Play Store. I personally use the one from the Play Store.

Now it’s a little tricky, go on your home page and place a “Kustom Widget” it’ll be just a grey box for now. You need to change the size of the box before installing the widget.
After that you need to click on the grey box and then click the widget you want in the list. The widget might not fit in the box, you can change its scale in the settings at the bottom or its position by selecting every item and clicking the arrow icon on the top.

If you still aren’t happy with the result. Delete the widget, replace it with a new “Kustom Widget”, change the box in another size and refollow the steps until you’re satisfied.

Customization: You can change the position and scale of the settings as said above. You can change what happens when you touch it by going into the “Touch” tab in the editor. Also check out the settings in the KWGT app if you want to choose which calendar or music player the widgets display.

# Other Widgets

If you want to use date/weather widget of the “Persona 5 Widget” just open the app, accept the permission it asks for and place the widget on your home screen. If you’re creative you can use your phone widget apps like I did.

# Icon Pack

Make sure you have downloaded the “Icons” folder. Next select a folder (which you can make in the Nova settings) or an app, click on the pen icon and tap the current icon. Choose an icon from the folder you downloaded and do this for every app you want.

# Persona 5 IM

The message app from Persona 5 is pretty neat, and you can have it too. Download “Persona5_IM.apk” and install it on your phone. To be able to message with your phone number you’ll need to set it as the default messaging app, it’ll probably ask for it in the app itself. Accept every other permissions and you’re set.

# Switching between launchers (Optional)

If you want to switch between your default launcher and Nova launcher where you set up the Persona theme, you could manually set the default launcher, then go on to change the wallpaper every time. However there’s a faster and more efficient way. This is for people who want to have 2 different themes or launchers.

The method I’ll show you doesn’t require rooting which is less complex to set up but it won’t be fully automated. Nonetheless switching launchers will still be very quick and easy. If you aren’t on Android 13 you might want to check the troubleshooting step under here. Anyway here is how you do it.

When you have the MacroDroid app on your phone download the two macros in the “MacroDroids Macro’s” folder. Open the app and click on the orange button that says “Export/Import”. Afterwards import the two macro’s from your storage. Go to your macro’s and check if they’re enabled.
DefaultLayout is to change from the Nova launcher to your default launcher, in my case the default launcher is One UI Launcher from Samsung. The PersonaLayout macro is the reverse, from your default launcher to the Nova launcher.

DefaultLayout Macro: The red area is where you set your triggers, this should be set as a custom widget button which you can later place on your home screen. If you click on the trigger you can configure it or delete it if you want to add another trigger. You can experiment by clicking on the add button in the top right.
The blue area is where you set your actions. I’ll talk about the “sent intent action” later, for now focus on the “set wallpaper”. You will need to select the wallpaper you want to be automatically set when you’re in your default launcher. Don’t forget to save and add the widget when you’ve finished.

PersonaLayout Macro: You should now see “Long Press” as a trigger, this is a settings tile which you can find by swiping down from the screen. Once again you can change the trigger in a widget or something else, you can also configure it if you want.
Under actions you need to click on “Set Wallpaper”, tap configure, select “Live Wallpaper” and select “Kustom”. This will set the Persona wallpaper.
If you want to hear a sound when the trigger sends a signal, configure the “Play Sound” action. At the bottom under “Select Audio Stream” you can select which kind of sound it is. Do you want it to act as a media or notification sound? Proceed to click on [choose file] and pick a sound from the “Persona5_SoundsProtagonistJoker” folder. I myself picked 0162.wav which is Joker shouting “Persona!”. Delete the “Play” action if you don’t want any sound. Lastly save.

Troubleshooting: I tested this on a Samsung and on Android 13 so the “Send Intent” action might not work on your device or version. The intent action sends a signal to open the switch launcher page which might, so in the configuration you’ll need the package and class of that popup. You could try searching those two things for your device if the macro doesn’t work.
This person has made one for Android 12: [MacroDroidForum](https://www.macrodroidforum.com/index.php?threads/change-your-launcher.2620/)

# **Links**

KLWP Pro:
\- Search it on [Google](https://letmegooglethat.com/?q=klwp+pro+apk)
\- Buy it on the [Play Store](https://play.google.com/store/apps/details?id=org.kustom.wallpaper.pro)

KWGT Pro:
\- Search it on [Google](https://letmegooglethat.com/?q=kwgt+pro+apk)
\- Buy it on the [Play Store](https://play.google.com/store/apps/details?id=org.kustom.widget.pro)

Nova Launcher:
\- Download it from the [Play Store](https://play.google.com/store/apps/details?id=com.teslacoilsw.launcher)

Persona 5 IM app:
\- From [CakeKing64 - Github](https://github.com/CakeKing64/P5IM-android-10-fix)

MacroDroid:
\- Download it from the [Play Store](https://play.google.com/store/apps/details?id=com.arlosoft.macrodroid)

Persona 5 Widgets:
\- 4 from [ Squidlie2214 - Reddit](https://www.reddit.com/r/Persona5/comments/9si4lj/comment/ebdx0p1/?utm_source=share&utm_medium=web2x&context=3)
\- 1 from [Tenma Hito - Reddit](https://www.reddit.com/r/Persona5/comments/c0zjwx/comment/er992x9/?utm_source=share&utm_medium=web2x&context=3)
\- 1 from the [Play Store](https://play.google.com/store/apps/details?id=blueberry.is.cool)

Icon Packs:
\- [Sidoma-Ken - Reddit](https://www.reddit.com/r/Persona5/comments/blir4g/comment/emp5r9i/?utm_source=share&utm_medium=web2x&context=3)
\- Unknown
\- [Edwin Agustinus - Google Drive](https://drive.google.com/file/d/1WrXJf2XJAwfadzXFh5nLitAHfl47fOEH/view?usp=share_link)

Persona 5 Sound Effects:
\- [The Sounds Resource](https://www.sounds-resource.com/playstation_3/persona5)
