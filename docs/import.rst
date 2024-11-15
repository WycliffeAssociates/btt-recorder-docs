Importing an Oral Project from the Box Server
=================================================

Please NOTE: Go to `Importing Source Audio <https://btt-recorder.readthedocs.io/en/latest/sourcefile.html#>`_ if you need instructions on how to import **source audio**.

Because BTT Recorder does not have a built-in capability to import files from other sources you will need to manually download the audio files from an external source into specific folder on the tablet.

When the recorded wav files are copied into the BTT Recorder folder structure, the project will show in BTT Recorder, and you can continue to work on it.

The BTT folder structure on the internal storage of your device looks like this:

   BTTRecorder > *language* > *type* > *book* > *chapter*
   
For example, recordings for chapter 1 of the book of Ruth in a ulb project with a target language of en-x-demo1 would be stored under this folder structure:

   BTTRecorder > en-x-demo1 > ulb > rut > 01
 
To create this folder structure, use the device’s file manager to create appropriate subfolders under the BTTRecorder folder, as described below.

To see how the folders should be named, look at the project’s files on Box. Here is an example:

   ta_ulb_b63_1jn_c05_v21_t01.wav
 
The “ta” before the first underscore is the language, so that is what you should name the first subfolder under BTTRecorder. After the first underscore is the project type, in this case “ulb”, so that is what you should name the subfolder of “ta”. You do not need to create the book and chapter subfolders. They will get created automatically when you download and extract a zip file from Box.

**Note**: Pay attention to the name of the book in the file name, in this case “1jn”, because you will need this name in a later step.

Create the Folder Structure on Your Device
-------------------------------------------

Before you begin this process, close BTT Recorder if you have it open.

To create the folders, perform the following steps:

1.	In the File Manager, navigate to the BTTRecorder folder.

2.	Tap the Plus sign if you see one, or tap the menu icon and select **Create Folder**. 

3.	Name the folder with the abbreviation for the language (in this case, “ta”). 

4.	When the language folder has been created, tap it to open it, and in a similar fashion create the project type subfolder (in this case “ulb”).

Download the Recordings
-----------------------

Now that the folders are set up on your device, you can download the recordings from the Box server by performing the following steps:

1.	In your device’s browser, enter the URL for the Box server, https://account.box.com/login, and sign in with your credentials.

2.	Navigate to the folder on the Box server where the recordings are stored. (You may want to click in the Search field at the top of the window, type in the target language name, and then tap on the language name.)

You should see separate subfolders for each Bible book that has been recorded.

3.	Find the folder for the book you want to download. Tap to open the folder.

4.	You can then tap **Download** at the top of the page, you may need to tap the 3-dot menu for the popup menu, and then you can tap **Download** on that.

5.	A message tells you that it may take several minutes for the download to complete.

6.	The file downloads to your device. A message displays when the download is complete. **Do not tap Open**.

7.	Return to the File Manager on your device and navigate to the Download folder. 

8.	Tap and hold the zip file that just downloaded until a checkmark appears to the left of it.

9.	Check to see that the zip file name is the same as the book name you made note of earlier, which was the book name shown in the recordings’ file names. In this example, the recordings showed a book name of “1jn”, but the name of the zip file is “1 John”. If the names are not the same, you must rename the zip file by performing the following steps: 

  *	Tap the three dots at the top right of the File Manager and select **Rename** from the drop-down menu. 

  *	In the Rename popup, type the correct name (in the example, 1jn) and tap **OK**.
    

Extract the Downloaded Files
-------------------------------

1.	Next you need to copy the zip file to the BTTRecorder > language > project type directory you created earlier. In the example we will copy 1jn.zip to BTTRecorder > ta > ulb.

  *	Tap and hold the 1jn.zip file until a checkmark appears to the left of it.

  *	Tap the three dots at the top right of the File Manager and select Copy to from the drop-down menu.

  *	In the Copy to popup window, tap Internal storage, then BTTRecorder, then your language folder (“ta” in the example), and then the project type folder (“ulb” in the example). Then tap OK.

2.	Now you can extract the recordings from the zip file. This creates the remaining folder structure: book, chapters, and individual verse or chunk recordings. To extract the recordings, perform the following steps:

  *	In the File Manager, navigate to the folder where you copied the zip file.
 
  *	Tap the zip file to open it, and in the Extract popup window tap Extract.

  *	In the “Extract to” popup window, ensure that the name is correct and then tap OK.

  *	It may take a few minutes for the files to be extracted, but when that is complete you should see the folder structure: book > chapters > verse/chunk recordings.

3.	If the file structure appears to be correct, you can delete the zip file out of the project type directory.

  *	In the File Manager, navigate back to the project type directory (the “ulb” directory in this example).

  *	Tap and hold the zip file to select it and then tap the trash can to delete it.  

4.	Now if you open BTT Recorder and look at your projects, you should see the one that you downloaded from Citrix and you can work with it as with any project.
 
