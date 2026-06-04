# Android 
Android is actually an open source operating software designed primarily for mobile devices such as smartphones and tablet.  
It was developed by the ***Google,Open Handset Alliance,and group of hardware,software and telecommunication companies***.  
Android is based on linux kernel and written in java and C++ programming languages.  

### Key Feature of Android
**-Open source**:Android is basically Open source OS.there is no need to purchase linsense to operate it bsaically free and easily avaiable online.And it's also allow other manufractures to use this without giving any money
**-Multitasking**:Android allows use to perform multiple task together by switching between multiple application simuntaneously it without any problem.
**-User Interface**:One of the core reason why android is so much is because of it's user friendly environment.they provide tons of custommization which user can do in to his devices as he like,providng customization in widgets,clock,wallpaper etc.
**-Security**:Android provide security to the user data,application and device itself.  **So in android provide security,**  -Application sandboxing:providing prevention from data acessing from other application,providing basically each application a isolate environment(in the aspect of isolate we say the store the data in private where other application cannot access the data.)  -Permission System:Apps cannot directly acees the data or resources like camera,mic,contact or location by own at first they need to take permission from user before doing it.  -Data Encryption: Android have this very usefull technique where stored data get converted into the encryption format and get store into the memory.So,if it result in prevention from unauthorizedd can't see or read your stored data.  -Google Play Protect:this is actually security build by the google to scans apps for any kind of malware.  -Secure App Signing: A mechanism that digitally sign the app so that if unauthorised user try to modify the app android will know and block that app services.
**-Compatability**:Android is very compatible with all kind of devices because it is easy to customize based on the device that result in more optimmization.
**-Connectivity**:If we talk in the aspect of connectivity the android provide a wide range support to the communication and different devices to communicate to different type of hardware and networks.  some connectivity features of android:
* Wi-FI - Connects to wireless network and the internet.
* Bluetooth - Connects wireless accessories like headphones,keyboards
* Mobile networks - calling services through cellular networks
* NLF-short range wireless commmunication 






# NFC (NEAR FIELD COMMUNICATION)
Near field communication is a short range  wireless communication between two devices used for transfering of data.it uses bluetooth for connectivity and for wifi transfering data. 4cm less very to close technolgy that enables data exchange between two devices places very close to each other.

# Secure App signing 

# Hash
when the app is developed there is a mathematical fingerprint is created a unique mathematical value calculated by the content of the file that fie contain eveyrthing that makes up the app-all the files,resource and assets.So, the Unique short value that is called mathematical fingerprint that is hash.
# Cryptography - Mobile App development
the science of securing the information using mathematical algorithm to prevent it from seen by unauthorised poeple or can see directly.
Caser cipher is a example of mathematial algorithm.
# Keystore
keystore is basically created by the developer to store all kind of cryptographic keys,especially the private key.
# Private key
baically private key is a cryptographic key that is only known to its owner.
used in  
1.Creating of the digital signatuer 
2.Encrypting and decrypting



# Digital Signature
A piece of cryptographic data which is attached to a app,a private key is used to create and that private key sign the hash of the app to create the digital signature.  
Digital singature is used to   
1.verify the developer singed in using the same private key.(here we are talking about whether the this digital singature is created using the same private key of developer or not.) for better understanding we gonna talk about the  
2.**By the Private key(security key) we can create a digital signature.and because of the digital signature we can know is anybody does any unauthorised modification.if there is any unauthorised modification then the digital singature will become **invalid result** and Android can detect that the app has been changed.And through public key can verify the signature.**
**After knowing the digital singature is broken or the app is being modified what does Android do ?**
1.Blocks Installation- it will refuse to install the app because the invalid signature or tampered content of the apps
2.Blocks Update-it will not update an existing app because the new version has mismatched signature,
3.Show Warning
4.Protects User data and device - so the android will prevents a any modification from pretender to be real.it will prevent from stealing password,personal information.installing malware,sending data to hackers
