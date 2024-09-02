# reMarkable-ScreenSaver
How to create a customized reMarkable screen saver.

Access the remarkable
Find the file to be changed
Bring the file to a place to be modified
Modify the file
Send the file back to the reMarkabl
Enjoy your work

# reMarkable directions for gaining access to the files system
[reMarkable support](https://support.remarkable.com/s/article/importing-and-exporting-files)
Connect your reMarkable with a USB cable to your computer.
Tap Settings.
Tap Storage.
Here you'll see the option Enable USB web interface. Select this.
Open a browser window on your computer and enter the address 10.11.99.1. 
This will show you a window of the content on your device.
You can now drag and drop files into this window to import them, or export files from the tablet by selecting them and clicking the Download button in the upper right corner.

Note: Your reMarkable must be connected with the USB cable before the USB web interface can be toggled on. You don't need to be connected to Wi-Fi or the cloud to use this functionality.

Instead of using a web browser, which is for transferring files, we are going to use Secure Copy to copy the suspended.png file to our local machine. This will enable us to edit the file with our favorite tool.

scp root@10.11.99.1:/usr/share/remarkable/suspended.png c:\temp\suspended.png