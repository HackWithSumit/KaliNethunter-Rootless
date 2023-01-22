# Kali-Nethunter-Rootless

![pngkey com-git-logo-png-3210881](https://user-images.githubusercontent.com/120317751/211306810-ed25c729-e73b-42f9-a9ea-ff75bbd8ce5c.png)


<B> Kali Nethunter 2022.4 </B>
<BR>
<BR>
<B> Requirements: </B>
<br> 

1. Termux (Include Bootloader):  https://f-droid.org/repo/com.termux_118.apk

2. Kali File manager: https://play.google.com/store/apps/details?id=com.marc.files&hl=en_IN&gl=US&pli=1

3. Kali Linux Nethunter OS: https://kali.download/nethunter-images/kali-2022.4/nethunter-2022.4-zerolte-nougat-kalifs-full.zip
  
4. Nethunter KeX: https://store.nethunter.com/repo/com.offsec.nethunter.kex_11407306.apk  
----------------------------------------------------------------------------------------------------------------------------


<B>Installation Guide:</B>

Step 1: First download above mention files

And the last thing to download is the Kali Linux ISO file and BASH Script. 
  
![image](https://user-images.githubusercontent.com/120317751/213934021-282ac8cc-2af1-4721-bcbe-e783ec97d221.png)

  
The iso file is huge it’s about 3 gigabytes so you need to drink some coffee while it’s downloading 😂

And here you guys need a files app because you can use this file Manager directly to navigate Termux storage, and trust me this is going to help you a lot while copying files in Termux storage.
  

Step 2: installing kali linux on android

       Now after you guys have downloaded all the necessary files open Termux.

So here m about to show you the offline installation process so we don’t need to update Termux repository and we are not going to use WGET as well.
  
Note guys all the commands that I have used in termux are case sensitive so make sure to type exactly or just copy and paste from here (Below)
  

So let’s set up storage by executing this command ” termux-setup-storage ”  now tap on enter and tap on allow. 
  
       termux-setup-storage 
  
![image](https://user-images.githubusercontent.com/120317751/213934237-0850427f-c70b-46cc-9ba3-c799334f1975.png)

  
Now type lS to confirm that you have a storage setup.
  
![image](https://user-images.githubusercontent.com/120317751/213934256-98a2b7a3-d63a-40b3-bff5-31f7e903a6b3.png)
  
  
Now as you guys have set up storage you guys need to go back and open the file manager application and navigate to the downloaded folder

 and then copy both of these files by tapping on the three-dot icon and then tap on copy to then tap on the burger icon then you should see Termux 
  
  
![image](https://user-images.githubusercontent.com/120317751/213934353-52a77b9a-c320-49b6-b14c-d102d3da7120.png)
  
 So tap on Termux again.. then simply copy both of these files in the root directory of Termux 

And it’s going to take some time as you can see copy progress at notification pannel.

Now we have both files pasted in Termux. 
  
![image](https://user-images.githubusercontent.com/120317751/213934384-e182199d-b6b7-4361-957b-ed32630f0952.png)

  
You can also check from Termux by executing the LS command
  
![image](https://user-images.githubusercontent.com/120317751/213934413-9d4d4758-ca2a-40f5-8434-2e56be4912ce.png)

  
Now you can see that we have a script file here ..

 So we need to make this script file executable so that we can easily install Kali Linux nethunter. 

To make it executable you need to execute this command.

      chmod +x install-nethunter-termux

Now tap on Enter button
  
![image](https://user-images.githubusercontent.com/120317751/213934447-3d6a06a6-1e3a-4c40-8017-00989388a7c6.png)
  
So as you can see that by typing LS command again we can see the script has is executable and it changes its color to green.

As I have told you this is a bash file so to execute this bash file in termux all you need to do is 

Type:
  
      ./install-nethunter-termux  
  
![image](https://user-images.githubusercontent.com/120317751/213934517-44942796-6e8b-435d-8a3c-83c28fd7de69.png)
  
  
And now tap on Enter and boom there we go.

 We have not used WGET or updated termux repositories and now we are installing this without any Hassle of error stuff.   
  
  
  

