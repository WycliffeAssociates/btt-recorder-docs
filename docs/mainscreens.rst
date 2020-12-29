Main Screens of BTT Recorder
----------------------------------

There are four main screens in BTT Recorder:

1.	`Home page`_
2.	`Project Management pages`_
3.	`Recording screen`_
4.	`Edit screen`_

These four screens are described below.

Home page
--------------
The first time you open BTT Recorder, after you create a user the Home page is shown. The right side of the page is blue with a Microphone icon, and the left side of the page is green with a List icon.

Right side (blue with Microphone icon):
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
If no project is shown
++++++++++++++++++++++++++++

Tap anywhere in this area to start a new project (see `Create a New Project <https://btt-recorder.readthedocs.io/en/latest/getstarted.html#create_a_new_project>`_).

If project is listed
++++++++++++++++++++
Tap anywhere in this area to navigate to the `Recording Screen`_ for that project.

Left side (green with List icon)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Tap anywhere in this area to navigate to Project Management page.

Project Management pages
------------------------
The Project Management page that first opens from the Home page displays a list of existing projects, if any. It also contains a 3-dot icon that enables you to access an Options menu.

Project list
^^^^^^^^^^^^^^^
If you have existing projects, this page displays a list of them. You can also tap anywhere on a project bar to invoke the chapter list for that chapter (see `Chapter list`_), or you can tap the **Plus icon** to start creating a new project (see `Create a New Project <https://btt-recorder.readthedocs.io/en/latest/getstarted.html#create_a_new_project>`_).
Each project in the list contains 3 columns that describe the project and 2 icons that you can tap.

Descriptive columns: 
++++++++++++++++++++
* Target language
* Project type
* Completion status

Information icon
+++++++++++++++++++
Tap the **Information icon** (gray circle with a white ‘i’ inside) for a project to open a popup window with details about the project.
The Book and Target Language are in the title of the Information popup. The window displays the following details:

* Project - The name of the book.
* Target Language - The common name followed by the language code in parenthesis.
* Translation Type - The choice made for the project. (Regular, UDB, or ULB)
* Unit - Either Chunk or Verse.
* Source Audio Language - If source audio is chosen its language is displayed here. You can tap the pencil to change the Source Audio language. ``*`` 
* Source Audio Location - If source audio is chosen its location is displayed here. You can tap the pencil to change the Source Audio location. ``*``
``*`` This opens the screen for selecting the source audio (see Select the Source Audio).

Tapping the Trashcan icon at the lower-left deletes your project. The other icons along the bottom right are for sharing your project (see `Sharing Your Recordings <https://btt-recorder.readthedocs.io/en/latest/sharing.html>`_).

Tap anywhere outside of the Information popup to close it.

Microphone icon
+++++++++++++++
Tap the **Microphone icon** to start recording the project. It opens the `Recording screen`_ to the first verse or chunk of the project.

Chapter list
^^^^^^^^^^^^^
On the Project list, tap anywhere on the project bar to invoke the Chapter list. 

On the Chapter list, you can: 

*	Tap the left arrow at the top left of the window to return to the Project list.
*	Tap in the chapter bar to invoke the verse or chunk list.

The Chapter list contains 2 columns that describe the chapter and 2 icons.

Descriptive columns:
+++++++++++++++++++++++++++++++
* Chapter number
*	Completion status

Compile icon
++++++++++++
Tap this icon to compile the individual verse recordings into a single recording for the chapter. See Create Chapter Recording.

Microphone icon
+++++++++++++++
Tap to invoke the Recording screen for this chapter.

Verse/chunk list
^^^^^^^^^^^^^^^^
On the Chapter list, tap in the chapter bar to invoke the Verse or Chunk list for that chapter. 

On the Verse/Chunk list, you can tap the left arrow at the top left of the window to return to the Chapter list.

Each verse or chunk is recorded separately, and you can record multiple takes of each verse or chunk. You can rate the takes to determine which one is used when you compile a chapter recording.

The Verse/Chunk list contains 2 columns that describe the verse or chunk and 2 icons.

Descriptive columns
+++++++++++++++++++++++
•	Verse number (or numbers if in chunk mode)
•	Number of takes (if more than one)

Microphone icon
+++++++++++++++++
Tap the Microphone icon to record a new take of the verse or chunk. See Recording screen.

Right arrow
+++++++++++++
Tap the right arrow to display the Take bar for the verse or chunk

Take bar
++++++++++
A take is one recording of a verse or chunk. Each verse/chunk may have multiple takes. There is not a separate page to show the takes. Instead, they are displayed in a bar under the verse or chunk, and you can navigate between them by using the left and right arrows. 

The components of the Take bar are:

1.	The timeline of the length of the audio take. The line expands left to right as the audio take plays. The time at the right shows the length of the recording; the time at the left increments as the recording plays.
2.	Garbage can icon - Delete a selected take. The numbering of the takes changes to reflect the lower number of takes available.
3.	Waveform icon - Invoke the Edit screen to edit the take (see Edit screen).
4.	Play icon - Play the recording. Tap the Pause icon (replaces the Play icon) to stop playing the recording.
5.	Checkmark – Tap to turn green, or if green, tap to turn black. The green color means that the take is approved to use when compiling a chapter recording. When the take is rated 3 stars, this checkmark is green, or you can just tap it to turn it green. Only one take per verse or chunk can be marked with a green checkmark.
6.	Star icon - Rate the recording. Only one take per verse or chunk can be rated three stars, indicating the take that is approved to use when compiling a chapter recording.
7.	Left or right arrow - Navigate among takes for a verse. Notice that the take number changes.

Using the Options Menu
^^^^^^^^^^^^^^^^^^^^^^^

The 3-dot menu (Options menu) appears only on the Project Management screen’s Project list and can be found at the far right on the top blue bar. Tap the 3 dots to invoke the Options menu.

On the options menu you can tap one of the following menu options:

*	Settings – View or change the settings of the program.
*	Logout – Sign out of the program. The program restarts at the User Account screen.
*	Help – View this documentation on how to use the BTT Recorder program. An internet connection is necessary to view the documentation.

The Settings window is mostly for information purposes. You can invoke the Settings window by tapping the Settings option in the Options menu. Although you can change some of the settings, it usually is not necessary. The Settings window contains the following information:

*	Source Audio Location – Sets the default folder that opens when you select a source audio location for a project. Although you can set the value here, the default location changes if you select a different location when defining a project. 
  *	Tap to open
  * Choose BTT Recorder and tap ALWAYS so that you never have to make the choice again. The window closes.
  * A file manager window opens so that you can navigate to the location of the file to use as source audio. Tap the file. 
  * The window closes. The next time you define a project’s source audio, the file manager opens to this location.
•	Source Language – It is not necessary to set a source language, because even if it is set you still need to define it each time you create a project.
  *	Tap to open
  * Search for the language from the list of languages.
  * Tap the language name. The window closes.
•	Add Temporary Language – Adds a language to the target language list that displays in BTT Recorder. You may need to do this if your target language does not appear in the target language list.
  * Tap to open
  * Enter the language name
  * Enter a code of exactly 6 characters
  * Tap ADD to add the language and close the window.
•	Update Languages From translationDatabase – Updates the list of target languages that displays in BTT Recorder.
  * Tap to run the update
  * The update processes
  * The pop-up message window closes when the update completes, and a success message briefly displays.
•	Update Languages From file – A file manager opens to enable you to locate the file to use.
•	Change Upload Server – Tap to change the server to which recording projects get uploaded.
•	BTT Recorder Version cannot be changed. It is displayed for information only.

Tap the back arrow at the top left of the Settings window to return to the Project Management screen.

Recording screen
----------------

You can navigate to the Recording screen by tapping the Microphone icon on either the Home screen or Project list, the Chapter list, or the Verse/Chunk list of the Project Management screen.

The recording screen enables you to record a take of a single verse or chunk. The Recording screen is initially set to a certain verse/chunk, depending on how you opened the Recording Screen:

*	If you opened the Recording screen from the Home screen or from the Project list of the Project Management screen, the Recording screen initially shows Chapter 1 and verse/chunk 1 of the project. 
*	If you opened it from the Chapter list of the Project Management screen, the Recording screen is initially set to verse/chunk 1 of the chapter whose microphone you clicked. 
*	If you opened it from the Verse/chunk list of the Project Management screen, the recording screen shows that verse or chunk. **Note**: This is the preferred method, because the Verse/chunk list shows you whether that item has been recorded already, so that you don’t unintentionally duplicate your work.

The Recording screen contains the following elements:
 
*	Top bar: Displays project information, chapter number, and verse/chunk number, with + and = icons to change the chapter and/or chunk/verse numbers.
*	Play icon to play the source audio, if you are using source audio (changes to Pause icon to stop/pause listening). You can listen to the source audio as needed to consume the ideas. You may need to replay the source audio more than once before you are ready to record the translation. 
  If you do not see the Play icon, you do not have source audio or have not defined it correctly (for example, you may not have created your project with the same verse or chunk mode as the source audio.)
•	Microphone icon to begin recording translation (changes to Pause icon to stop/pause recording)

To return to the screen where you opened the Recording screen, tap the device’s Back button.

Edit screen
------------

A take is a recording of a verse or chunk; a verse/chunk can have multiple takes. You can navigate to the Edit screen for a take by tapping the Waveform icon on the Take bar of the Verse or Chunk list.

The edit screen enables you to edit the take of a verse or chunk in the following ways: 

*	Cut out sections of a recording
*	Insert new sections into a recording
*	Place verse markers
*	Rate the recording

Cutting
^^^^^^^^^^

The action of removing a section of a recording is known as a "cut". 

To make the cut you first mark the section to be deleted by performing the following steps:

1.	Position the audio at the thin blue line for the beginning of the recording to be removed. **NOTE**: The blue line does not move. You need to do the press-and-hold action to move the recording to the blue line.
2.	Set the beginning point of the cut by tapping on the flag icon. This inserts a marker where the cut will start.
3.	Drag the recording by holding your finger on the screen and sliding to the left until the end of the part to be removed is at the blue line.
4.	Tap the upside-down flag button. This marks the section for deletion.

**OPTIONAL**: Tap the **Play icon** to listen to the section that will be removed.

**Do you want to change the amount of recording that is selected?** Press-hold-drag on the upside-down flag to increase or decrease the amount of the selected recording.

**Need to start again?** Tap the crossed-off flags icon to remove the flags and start at step 1.

Tap the **Scissors icon** to cut the section you have marked for deletion.

**OPTIONAL**: Tap Play to listen to the take to ensure it is correct. If you made a mistake, tap the Undo icon to restore the deleted section.

Tap the **Save icon** to save the edit. BTT Recorder saves the edited take and returns to Project Management.

Inserting
^^^^^^^^^^^

Sometimes you may want to insert a missing part into the translation. For example, to re-record a section of the take, you can first cut it and then insert the replacement for the section.

To insert a section into the recording, perform the following steps:

1.	Position the audio at the thin blue line for where the new audio will be added in (use the press-hold-drag action, or tap in the lower waveform, or listen to the recording and tap **Pause** when you are at the correct place.)
2.	Tap the **Add a Recording** icon   in the top gray bar. This opens a new recording session for the part to be inserted. **NOTE**: The bar at the bottom of this window is green.
3.	Tap the **Microphone icon** to start recording.
4.	When finished, tap the **Pause icon**.
5.	To insert the new recording, tap the **Checkmark icon**.
6.	A pop up appears stating it is inserting recording … please wait.
7.	The original target language recording opens with the inserted recording added.
8.	To save the file tap the **Save icon**. A ‘Saving’ pop-up appears.

Once the program is done saving, the Project Management verse/chunk list screen opens with a new take added at the bottom of the take list. For example, if there were 3 takes before recording the new section, the added take is Take 4.

Placing verse markers
^^^^^^^^^^^^^^^^^^^^^

Verse markers are available only when recordings are done in chunk mode. To insert the verse markers, perform the following steps:

1.	Open the recording in the Edit screen.
2.	Tap on the bookmark icon. The Verse Marker window opens.
  *	Notice the yellow playback bar on the bottom of the window.
  *	The top gray bar has the number of markers left to put into place.
  * A verse marker is at the beginning of the recording.
3.	Locate the end of the verse:
  * Tap the **Play icon** to play back the recording.
  * Tap the **Pause icon** to stop the playback when it is at a verse ending.
  * Other ways of finding the correct spot in the recording:
      *	Use the press-hold-drag action to move the playback forward or backward until the verse division is on the blue line.
    OR
      * Tap in the bottom waveform.
4.	To add the verse marker, tap the **white flag** on the yellow bar at the bottom right of the screen.
5.	If there is another verse to mark: Continue to listen to the playback for the next ending of a verse.
6. If you need to move a verse marker, you can use the press-hold-drag action to move a verse marker flag forward or backward on the waveform.
7. When there are no more verse markers to place – Tap the back icon (Android back) found under the yellow bar.
8. The Edit screen opens and shows the verse markers. Tap the **Save icon** at the bottom right of the screen to save and return to Project Management.

**HINT**: You might want to rate this recording before saving.

Rating
^^^^^^^^

To indicate the quality of the recording, you can add a star rating to it. The star ratings are used by the program to determine which take of a verse or chunk to use when compiling an entire chapter recording (see `Creating a Chapter Recording <https://btt-recorder.readthedocs.io/en/latest/compiling.html`_).

1.	Tap the Star icon (either on the verse/chunk bar or in the top gray bar of the edit window). The ‘Rate this take’ window opens.
2. Decide on a rating:

  * Tap the left star if the recording is not the best – the star turns red.
  * Tap the middle star if the recording is fine but could be better – the stars turn yellow.
  *	Tap the right star for an excellent recording – the starts turn green. Only one take per verse/chunk can be rated 3 stars, because this indicates the accepted take.
  
2.	Tap **OK** to save.


