Instructions how to run on lineageos 18.1 microG 
Nanodroid + Playstore to run


1. install rom + restart magisk

2. go through setup , do not make microg settings

3. download the required two files 1. the nanodroid and 2. microg installer Revived from here >>>> Nanodroid + Microg_installer_Revived <<<<<

4. open the Magisk Manager and follow the instructions will force a reboot of the device

5. go back into the magisk manager and install the nanodroid it will take a little while until everything is ready restart it


6. this may take a while until it automatically boots into twrp 2-3 min.

7. you should be in the twrp now

8. install now the downloaded microg_installer_Revived then reboot the system 
(this is the current version 1.11.0-0 of nift4 (prev. Hieu Van) which is available via magisk )

9. the system should now boot which it does 100%. 
and lo and behold PlayStore + AuroraStore is present since I entered 30 in nanodroid setup

10. go into the microg settings do a self check everything should be fine 
microg settings activate all three under the account otherwise there is an error message in the PlayStore

11. so now let's open the playstore and log in supi that works too

Push message:

I would like to know now whether puch messages work

for this I download the app push notification tester <<< here or from the PlayStore .

start the app it should actually be everywhere a hook is unfortunately not at Register Push 
how do we solve this ?

very simple go in the microg settings under cloud messaging top right on the points ... Advanced 
and activate new apps confirm then restart

go back to the microg settings and activate the three under the account again 
start Push Nonfiction app again if no message appears restart the phone
and look in the microg settings if everything is still activated 
I had to restart 2-3 times until Push Nonfiction got the message see screenshots 
confirmed the whole thing and now all hooks are set

let's go to Next at Push Nonfiction press REQUEST NOTIIFICATION 
you should now have received a message in the statusbar 
and a green area with Success Congratulation.

# You can still correct for errors,
A maybe this here also wril the aurona Store is not up to date  
Must be in system/apps and in system/priv.apps the store and delete the service 
before you can install the current aurona store.
