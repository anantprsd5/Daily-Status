# Daily-Status

## 15 October 2016

* Setted up Android Studio on my PC successfully.
* Started the exercise from udacity to create a weather app.
* Learned about setting an app icon to any android project.
* Setted up the starter code for the app and installed the virtual device for testing applications.

## 17 October 2016

* Learned to turn on the developer mode in an Android device and to enable USB Debugging for testing the application on my mobile phone.
* Learned some basic command line Commands for compiling the code, creating an Apk file, installing it and finally running it on my Android device.
* Learned about building a UI with a layout editor by dragging widgets into a visual design editor instead of writing the layout XML.
* Got to know about the various layouts in an Android application which are described below:

#### &nbsp;&nbsp;&nbsp;&nbsp; Linear Layout:
* It is a view group that aligns all children in a single direction, vertically or horizontally. 

#### &nbsp;&nbsp;&nbsp;&nbsp; Relative Layout:
* It is a view group that displays child views in relative positions. The position of each view can be specified as relative to sibling elements (such as to the left-of or below another view) or in positions relative to the parent RelativeLayout area (such as aligned to the bottom, left or center).

#### &nbsp;&nbsp;&nbsp;&nbsp; List View: 
* ListView is a view group that displays a list of scrollable items. The list items are automatically inserted to the list using an Adapter that pulls content from a source such as an array or database query and converts each item result into a view that's placed into the list.

#### &nbsp;&nbsp;&nbsp;&nbsp; Grid View:
* GridView is a ViewGroup that displays items in a two-dimensional, scrollable grid.

## 22 October 2016

* Learned to define a UI of the app within the XML files in the resources folder.

* Learned about the MainActivityFragment which is java program used to display the cotents defined in the XML files.

* Got to know about adding or changing layouts in the fragment_main.xml file in the Layout folder. This thing can also be done using the auto import settings of the Android Studio.

* To enable auto-import, go to Android Studio > Preferences > Editor > General > Auto Import check all the boxes and insert all imports on paste

* Got to know about Adapters in Android which are the glue that allows us to bind our underlying data to our user interface elements.

## 5 November 2016

* Today I got to know about DNS spoofing by a session conducted by Aravind.

* Enrolled into Udacity Android Developer nanodegree program which is free for a month beacuse of github education pack and I am currently working on the first leg of the project which is about adding few buttons in an android application using relative layout which on being clicked will show a relevant message.

## 6th November 2016

* Today I completed the first leg of the nanodegree project.

* It was about Creating a layout for the main activity, adding a title, buttons for each app, and a style of our choosing.

* To define a function in the main activity which displays the name of the particular app on the button being clicked as a toast message.

* The link to my project : _https://github.com/anantprsd5/Udacity_Nano_ .

## 8th November 2016

* Today I continued with my nanodegree course. I got the review of the first project which I submitted, in that everything was perfect except for the fact that I didn't thought about the different screen sizes and different orientations so some part of the display was not visible in landscape mode. For this the suggested to implement linear layout inside of a scroll view. After that everthing works fine.

* Continued working on the second leg of the project of creating a weather app got to know about implementing list views and working with Array Adapters.

* Hope to complete the second project soon.

## 13th November 2016

* Today I continued with my nanodegree course. I got to know about the AsyncTask which allows you to perform background operations and publish results on the UI thread without having to manipulate threads and/or handlers. 

* I am currently working on replacing my fake data in the list view with the updated real weather data using the openweathermap API.

* Also I was working on the bug of my organisation's app in which the top and bottom content of th login and signup screen was not visible due to the lack of scroll view in it.

## 14th November 2016

* Today I was working on a bug in the Susi-android chatbot application. The bug was that when we enable the text to speech option it offers a file download for the selected language in text to speech settings of the phone. In that I am supposed to fallback to the english _US_ Locale inspite of offering a file download.

* The main problem is that I am unable to reproduce that bug as in my phone for every language it is working fine. Even in the codebase I can see that the language was just set to _US_ and it is just responding in the english _US_ language.

* I am contacting the developers of the organisation to get some help with the issue.



