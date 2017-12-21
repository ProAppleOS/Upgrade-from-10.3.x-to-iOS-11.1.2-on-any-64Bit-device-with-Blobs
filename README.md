- Copyright by iloveapple1999 © ;
- MADE BY @iloveapple1999 on Twitter; 
- ANY QUESTION? -> @iloveapple1999 on Twitter 

# Upgrade from 10.3.x to iOS 11.1.2 on any 64Bit device
How to Upgrade any 64Bit Device from 10.3.x to 11.1.2 with Blobs

DOING THIS IS AT YOUR OWN RISK! I'M NOT RESPONSIBLE FOR ANYTHING.

```Requirements:```
- a Mac (or virtual Machine) on macOS 10.12.6 or newer
- any 64 Bit device on 10.3.x
- SHSH Blobs for iOS 11.1.2 
- Xcode 9 or later 


```Currently Supported Devices for UPGRADING```
- iPad Mini 2 (WiFi)            iOS 10.3.1
- iPad Mini 2 (Cellular)        iOS 10.3.3
- iPhone SE                     iOS 10.3.2
- iPhone 5s                     iOS 10.3.1 - 10.3.3
- iPhone 6                      iOS 10.3.1 - 10.3.3
- iPhone 6s                     iOS 10.3.2 - 10.3.3
- iPhone 7                      iOS 10.3.1 - 10.3.3
- iPhone 7 Plus                 iOS 10.3.1 - 10.3.3

If your device isn´t supported, you CAN upgrade BUT you need to find Offsets and need to put it in the v0rtexNonce Xcode Project in the offsets.m file and compile it! 
- How to find Offsets for v0rtexNonce (https://goo.gl/qq6hFG) 
- Video Tutorial for finding Offsets for v0rtexNonce (https://goo.gl/f6bmVz)
- Here are some Offsets but thes are NOT tested: https://goo.gl/W35oMy



                                                 DOWNLOADS:

- Download iPSW for your Device! You need iOS 11.1.2 IPSW. You can Download iPSW here: www.ipsw.me 
- Download & install Xcode (Xcode from MacAppStore).
- Download v0rtexNonce. (https://github.com/arx8x/v0rtexNonce)
- Download THIS fork from futurerestore (https://goo.gl/Y4qfai)

                                                 Lets Go :)

1. Open ```v0rtexNonce-master```folder
2. Double click on ```v0rtexNonce.xcodeproj```
3. Click Open
4. Go to ```Xcode -> Preferences -> Accounts -> click + -> Sign in with your AppleID``` (no developer account needed)
5. Close ```Accounts``` Window
6. Click on the left top at the blue file named ```v0rtexNonce``` example: https://imgur.com/a/VflY1
7. Change the ```Bundle Identifier``` to something you want, like for example ```test1```
8. Click at the middle on ```Unknown Name``` and select your AppleID. Click on that ```Personal Team```
9. Wait until the Red text is gone
10. Plug in your device and select at the top next to ```STOP``` button your Device.
11. Click on ```Play``` Button.
12. Unlock your device.
13. Ignore the popup in Xcode saying ```Could not launch v0rtexNonce```
14. Open ```Settings``` on your iPhone. Go to ```General -> Profile & Device Managment -> Click on your Apple ID -> Click on Trust -> Trust again```


                            Now you got your v0rtexNonce set up. Great Lets go further :D
                                     
                                     
1. Create a folder on Desktop and name it ```Upgrade```
2. Put the iOS 11.1.2 IPSW you downloaded at the beginning into the ```Upgrade``` folder.
3. Open ```futurerestore_macos``` folder and put the file ```futurerestore_macos``` into the ```Upgrade``` folder.
4. Copy your SHSH2 blob from iOS 11.1.2 and put into ```Upgrade``` folder.
5. Rename your Blob name to ```blob.plist```        NOT ```blob.shsh2.plist```!
6. Click ```use .plist``` 
7. Open your SHSH Blob.
8. Scroll to the very bottom and you'll see a long string of characters that is SIMILAR to ```0x28tf5c185sj9```, but NOT IDENTICAL

9. Now Open v0rtexNonce on your Device. If your Device isn´t supported or your Offsets are wrong the App will Crash.
10. If your device is supported and the App opens and the popup ```Exploit failed```comes up Reboot and Try again until you get a Nonce. In the App looks it like this    ```0x23ae4a983ds7```
- Keep in mind! The Exploit isn´t that reliable and does have a relatively low success rate, so keep trying
11. The app should look like this if it worked (https://imgur.com/a/MHRim)
12. So, Paste that nonce you got inside your Blob into the ```v0rtexNonce``` app on your iDevice and click on keyboard ```return(enter)``` to set the nonce on your device. 
- Then a popup should come with ```The generator has been set``` 
- example: (https://goo.gl/57gGwi)
    
    
                                        Now go back to your Mac!
 

1. Close the your SHSH Blob file (don´t change anything inside the blob file)
2. Rename your blob to ```blob.shsh2``` NOT ```blob.shsh2.plist``` or NOT ```blob.plist.shsh2```
3. Click ```use .shsh2```

Now you are all set for your Upgrade! Now you should have this in the ```Upgrade``` folder on Desktop:
- blob.shsh2
- futurerestore_macos
- iOS 11.1.2 IPSW


                        NOW THE UPGRADE PROCESS! Be patient! Don´t type anything wrong!
                              
                              
1. Open Terminal
3. write ```cd (drag your Downgrade folder into Terminal)``` and enter
3. type ```ls``` and enter
4. now you should see all the files in your ```Upgrade``` folder
5. drag ```futurerstore_macos``` file into terminal and click enter (you should see lots of commands)
6. write this
- ```./futurerestore_macos -t (drag blob) --latest-sep --latest-baseband (drag iphone11.1.2.ipsw)``` 
- Good example here: https://imgur.com/a/02EnO
7. Plug your Device in
8. Unlock your Device
9. CROSS FINGERS AND click ```Enter``` in Terminal
- ITS NORMAL THAT YOUR SCREEN OF DEVICE TURNS INTO GREEN (JUST IN THE UPGRADE PROCESS)!
10. Now it should work 
11. Wait about 5-10 Minutes
12. Your Phone now Restart.
13. Set up your Device
14. Install a Jailbreak if one is out :)


                                         DONE! ENJOY YOUR JAILBREAK :D
                                             
- THANKS TO @tihmstar for futurerestore
- THANKS TO @siguza for v0rtex Exploit
- THANKS TO @arx8x for v0rtexNonce
- THANKS TO @firstencounter for the futurerestore fork that works with iOS 11
                                             
                                       MADE BY @iloveapple1999 on Twitter 
