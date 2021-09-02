# Enable-null-safety-in-flutter
There are few steps to followed to enable sound-null safety in flutter:

Step 1: 

Check Latest Dart Version(It should be Dart 2.12 or later:)
   
>> dart --version

Step 2:

Update the dart version, the above point not satisfied using the command.
>> dart pub upgrade --null-safety

>> dart pub get

Step 3:

Run the below command to know what are libs in your project needs to be upgraded to the latest null safety.
>> dart pub outdated --mode=null-safety

Step 4: 

Finally, run dart migration command which performs null safety migration on existing project(Existing project).
>> dart migrate


:) :) :) I hope this will help you to solve this issue in latest versions of flutter. 
  
  Thank You , Have a great life..... (".")

