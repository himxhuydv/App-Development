# Core Components of Android Application
1.Activites:Activities Is a components of android application where a single screen UI components  of the applications interact with the User.
2.Services:Services is the android application that runs in background that execute long running operation without the user interaction.
3.Broadcast Receiver :It's a android application that receives and responds to the system wide messages.
4.Contest Provider:it's a android application that works with the multiple application for storing data,contact,messages etc.between them in a structured interface.
**Suppporting Components**
1.Intent:it's basically communicate between compenents 
for ex: 
activity=open another activity
activity=starts service 
broadcast receiver=sends a message 
2.Fragments:the small portion of the activity have user interaction.useful for flexible layouts.
for ex:
in the activity 
Profile info in the right corner
3.Views & layout: 
View:
Ui in the application that interacts with the user and display content.
Layout:
container that used to arrange multiple view into the screen.
4.Widgets:small interactive Ui  components placed on the home screen.
5.Notification:alert the user without affecting the current activity
6.Manifest file:It's actually application information file that actually contains the essential information about the application.it's define app components,permision,configuration.

for ex:
<manifest file>
   <application>
       <activity android:name=."Mainactivity">
            </activity>
        </application>
</manifest file>

