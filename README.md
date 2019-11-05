# HOTEL BOOKING AND MANAGEMENT SYSTEM

## INTRODUCTION

Hotel management is the system involving the management of all things related to
the hotel business. As a field of study, it involves learning the management
techniques that cover all aspects of managing a hotel business including hotel
administration, marketing, housekeeping, accounts, maintenance, food
management, catering, and beverage management. The goal behind learning this
management system is to run a hotel properly while managing all aspects of the
business. Hotel Management System has become an integral part of tourism with the
increase in lifestyle and indulgence in luxurious way of living. The scope of
opportunities in the hotel industry is vast. This industry is in constant change with
the evolution of IT. There are so many departments that contribute to different
aspects of running a hotel. This also includes recreation, public relations, security,
and computer applications besides the above-mentioned mainstream specializations.


Looking at the broader perspective and analysing the need for fair customer
experience we initiated to work on the project “HOTEL MANAGEMENT
SYSTEM” in which we have tried to show how the data in hotels is managed. This
has been achieved by dividing the project into various modules. Customer is
provided with different services like registrations, check-in, check-out and selection
among different rooms provided by the hotel facility. Developing a customer
friendly module wherein the customer can make a new account or also has an option
to directly login if the account is previously registered with the hotel. Customer can
enquire about rooms availability and book according to the dates securable for the
duration of stay. The hotel provides an option of three main type of rooms to be
chosen from; namely suite class, single and double rooms. The module is designed
in such a way that the system analyses the input check-in and check-out date and
upon the check-out the customer is provided with a printed bill. To this we also
added another important feature to volumize the customer experience with the hotel
thereby including a feedback section wherein the customers can freely voice their
opinions, provide suggestions as to how the service can be better provided and last
but not the least rate their staycation with the hotel.

## DESCRIPTION REGARDING PROJECT 

  **Let's discuss the features of the project in deep**
  
Initially, after the splash screen goes off, login window pops up and if you have already registered with the server of the hotel, then you just need to enter the username(basically the name of the user) and the passsword. The system then tries to locate the username and its corresponding password, if the entered credentials are correct, then it will redirect the user to the HomeScreen. If the details are incorrect, the user needs to enter the correct details again(the feature of changing the password is missing for now ☹).

If the user is fresh to the server, then he/she can create their account.
For creation of the new account,the users needs to enter their phone numbers and email as well.
The system will then autenticate if the entered values are correct or not
  for eg,
    If the phone number consists any alphabets or if the number is <10, then the authentication fails !
    Same is the case with email, it will check for the proper format of email(xyz@domain.com)
Once the authentication is successful, the register button will be activated pressing which will affect into new account !

The HomePage displays the username , feedback panel, and room booking options.
There are 3 room types namely Suite, Single-room and Double-room.
The count of the rooms for each type is 5.
After selecting the type of room, user needs to enter the checkin and checkout dates following which the system will look onto total available rooms.
If the room is available, the the slot is allocated to the user, else he/she has to select some other dates.
Details of the stay will be shown on the screen and once the user confirms the booking, bill will be printed(can also be saved as pdf).
After booking the user is again redirected to the home page, but now Room booking for that user is disabled while he can now get the details on mail or sms (for this you need to pay the domain you are applying to).
The user can also rate and share their experience under the "Feedback" option.

## BUILT WITH

[NetBeans](https://netbeans.org/downloads/8.2/start.html?platform=windows&lang=en&option=javaee)\
[Java](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)\
Apache Derby database

## PRE-REQUISITE

This project done completely using Java and JavaFx with implementations of SQL queries for the data storing.
So one must be aware with the same.

## INSTALLATION

1. Download the NetBeans IDE from the given link in the built with section. The link provided is of version 8.2 in which I developed but it is recommended to go with NetBeans 11 beacause I saw many struggling with Derby-Java connection with the 8.2. But give a try once to 8.2 and if it doesn't work then mail me for the guidance.
2. Import the project into the IDE.
3. Under Libraries, add the jCalender jar file(provided above) and create your library and add the db-derby zip(also provided above)
4. Once done with all the installations, you need to connect your project with the Database.
    * Go to services
    * Then to Databases
    * Then to JavaDB
5. To run the omplete project press the run-project button or you can individually run each frame to verify your layout.

## AUTHOR

Ashwith Poojary : [Ashwith25](https://github.com/Ashwith25)

## BUGS
There are many bugs from IDE which I encountered personally while I was developing this project.
* Database Connectivity : This has been a major issue in this IDE because many of my colleagues faced this issue where their project wasn't able to connect to the Netbeans.
* Running of individual Frames : As I mentioned above, you can run the frames individually, but sometimes the problem is that the project is not refreshed/updated so you need to run the project and then open then open the required frame once the main project is closed. So basically pressing the run-project button acts as a refresh for your project.
* One more problem I found is, you cannont run the main project if the previously opened frame/project is not closed properly. So you need to close the task from the task Manager. This is because your java links to any one project at a time so you need to free that correctly after execution.

## CONTRIBUTING
When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with me before making a change.

## DOUBTS AND QUERIES
 Feel free to ask any doubts in any part of the project or SQL queries or for the installation part.
 Even if you encounter some other bugs not mentioned above, just mail me the issue and I'll try to resolve it to my best.
 *contact me : email : pashwith25@gmail.com*
