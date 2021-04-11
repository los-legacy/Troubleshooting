![Download](https://user-images.githubusercontent.com/24758741/114311822-97877e80-9af0-11eb-9455-6c300e30a8b3.png)



Instructions how to run on lineageos 18.1 microG with Nanodroid Patched Playstore

1. Install rom and magisk then reboot

2. Set up Lineage OS , do not make microg settings

3. Download the required two files 

    3.1 [Nanodroid](https://github.com/los-legacy/Troubleshooting/releases/download/v1.0/nanodroid.patched.playstore.only.zip)

    3.2 [microG_Installer_Revived](https://github.com/los-legacy/Troubleshooting/releases/download/v1.0/microG_Installer_Revived-Revived_1.11.0-0.11100.zip/)

4. Open the Magisk Manager and go the to module tab**
5. Select install from internal storage and select the nanodroid.zip, if its finish tap on reboot
![Screenshot_2021-04-09-22-59-03 (1)](https://user-images.githubusercontent.com/24758741/114313634-7e360080-9af7-11eb-8f0e-c80ee1ab9411.png)
6. This cause maybe a "bootloop" but its boots automatically into twrp (2-3 minutes)
7. You should be in the twrp now
8. Install now the downloaded microg_installer_Revived then reboot the system 
 
(this is the current version 1.11.0-0 of nift4 (prev. Hieu Van) which is available via magisk )

9. The system should now boot which it does 100%. 
and PlayStore should be present because I edit the entry to 10 in nanodroid setup

10. Go into the microg settings, do a self check everything should be fine (if not granted the permissions)

11. activate all three points under the account settings otherwise there is an error message in the PlayStore

12. So now let's open the playstore and log in, this should also works

13. To be able to install the purchase apps you have to tap 7 times on Playstore version until it comes that you are a developer


** If magisk reported magisk is not installed, flash magisk again. if magisk reported app is not installed install the app again
