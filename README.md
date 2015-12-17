# HoloEverywhere
Your project uses this library and crashes in Android M? This fork has the fix

# Note
This "fork" is based in the source code of the library "HoloEverywhere" created by github user @Prototik and the library "ActionBarSherlock" created by github user @JakeWharton , both of this libraries are  
### DEPRECATED  
.

# If those are deprecated, why this "fork" exists?

Some apps uses this libraries and those libraries crashes in Android 6+, the optimal fix is remove this libraries from your porject but, if you need the fix ASAP, removing the libraries can be quite slow.

# How to implement this fix

1-. Remove all the dependencies of "HoloEverywhere" and "ActionBarSherlock" of your project (ALL OF THEM, jar, aar, maven, module, etc).

2-. Download a .zip of this fork (or clone it).

3-. Go to Android Studio/File/Project Structure

4-. Click the + icon in the upper left corner of the window.
![plus-icon](https://k60.kn3.net/55871955C.png)

5-. Choose "Import Gradle Project"
![module](https://k60.kn3.net/ADA667B1E.png)

6-. click in the [...] icon and navigate to the root folder of the cloned/.zip extracted copy of this fork, then add a library.

Rename the module if you want.
(You will need add the other library in this way)

7-. When you added both of those libraries, return to "Project Structure" main dialog.

Select your main app and go to "dependencies" tab, there, click in the + icon in the bottom, then select "module dependency" and select "HoloEverywhere".

Then, go to "HoloEverywhere", next, go to "dependencies" tab, click in the + icon in the bottom, then select "module dependency" and select "actionbarsherlock".
![dependencies](https://k60.kn3.net/403235569.png)

8-. Enjoy
