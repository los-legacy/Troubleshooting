Nanodroid solution

Apps are not receiving Push messages

go to microG Settings / Google Cloud Messaging and check if it is connected
ensure you don't have an adblocker blocking the domain mtalk.google.com it is required for GCM to work
when using Titanium Backup or OAndBackupX first install the app only (without data) and start it, this will register the app, afterwards restore it's data
when restoring the ROM from a TWRP backup GCM registration for apps is sometimes broken. You may use the following command to reset GCM/FCM connection(s). App(s) will re-register when launched afterwards:

nutl -r APPID (eg.: APPID = com.nianticlabs.pokemongo) or nutl -r (for all applications)

if you can't make any app registering for Google Cloud Messaging, try the following

open the Phone app and dial the following: *#*#2432546#*#* (or  *#*#CHECKIN#*#*)

Push notification tester

For this I download the app [push notification tester](https://github.com/los-legacy/Troubleshooting/releases/download/v1.0/com.firstrowria.pushnotificationtester_2.9.apk) or from the PlayStore.
Start the app it should actually be everywhere a checkmark is unfortunately not at register .....Push how do we solve this?
Very easy go in the microg settings under cloud messaging tap right on the points ... Advanced and activate new apps confirm then restart.
Go back to the microg settings and activate the three points under the account again start Push Nonfiction app again if there is no message restart the phone again.
Look again into microg settings if everything is still activated, I had to restart 2-3 times until the push notifiction permission pop-up appeared

<img src="https://user-images.githubusercontent.com/15938117/114340288-86be2380-9b57-11eb-86d4-8778981d9622.png"
   height="256"><img src="https://user-images.githubusercontent.com/15938117/114340289-87ef5080-9b57-11eb-9d83-f1bb2889a292.png"
   height="256">

Let's go to Next at Push Notification press REQUEST NOTIFICATION you should now have received a notification in the status bar and a green missing with Success Congratulation.

<img src="https://user-images.githubusercontent.com/15938117/114340577-2976a200-9b58-11eb-81c9-c6f18ce01889.png"
   height="256"><img src="https://user-images.githubusercontent.com/15938117/114340580-2aa7cf00-9b58-11eb-8bbb-cf67aa4ac022.png"
   height="256">
