

#Software Requirements Specification Document ##for ##chatbot for facebook messenger ####Version 1.0 approved

##Table of Contents #####Table of Contents ............................................................................ ii #####Revision History.............................................................................. ii

    Introduction.................................................................................................................1
        1.1 Purpose ....................................................................................................... 1
        1.2 Document Conventions.................................................................................. 1
        1.3 Intended Audience and Reading Suggestions..................................................... 1
        1.4 Product Scope ............................................................................................... 1
        1.5 References.................................................................................................... 1

    Overall Description.........................................................................................................2
        2.1 Product Perspective ...................................................................................... 2
        2.2 Product Functions ......................................................................................... 2
        2.3 User Classes and Characteristics ....................................................................2
        2.4 Operating Environment................................................................................... 2
        2.5 Design and Implementation Constraints........................................................... 2
        2.6 User Documentation ...................................................................................... 2
        2.7 Assumptions and Dependencies ..................................................................... 3

    External Interface Requirements ....................................................................................3
        3.1 User Interfaces ............................................................................................ 3
        3.2 Hardware Interfaces..................................................................................... 3
        3.3 Software Interfaces ..................................................................................... 3
        3.4 Communications Interfaces .......................................................................... 3

    System Features...........................................................................................................4
        4.1 System Feature 1........................................................................................... 4
        4.2 System Feature 2 (and so on).......................................................................... 4

    Other Nonfunctional Requirements..................................................................................4
        5.1 Performance Requirements............................................................................ 4
        5.2 Safety Requirements...................................................................................... 5
        5.3 Security Requirements................................................................................... 5
        5.4 Software Quality Attributes............................................................................. 5
        5.5 Business Rules.............................................................................................. 5

    Other Requirements .......................................................................................................5
        Appendix A: Glossary...........................................................................................5
        Appendix B: Analysis Models.................................................................................5
        Appendix C: To Be Determined List.........................................................................6

###Revision History No revision history available yet.

###1. Introduction ####1.1 Purpose

This document is intended to provide a detailed description of the requirement specifications for a chatbot to be built within Facebook messenger. There are no revisions or number releases of this document so far therefore this will be the first release of its kind with version number (Version 1.0.0). The document will specifically focus attention on reqirements specifications for a news chatbot as the product in question.

####1.2 Document Conventions

####1.3 Intended Audience and Reading Suggestions

This document is meant to be used by the developers, project managers, testers and documentation writers of the Facebook messenger chatbot. The developers will need to include the details specified in this document to make the product conclusive as required, hence they are part of the audience to which it is addressed. The sequence of reading will be as follows….

####1.4 Product Scope

Chatbots are a new but rapidly growing technology that is being integrated within many existing social media applications like Facebook messenger, skype, kik among others. This technology allows users of those social media applications to carry on conversations with a computer the same way they would with fellow humans. For the one in question, it is intended to be a news chatbot specific to Facebook messenger that will allow users to subscribe for in order to access news as it comes in from sources, request for topics of choice and even unsubscribe from at any time of wish. This is aimed at extending useful information to social media platforms specifically Facebook messenger which has registered overwhelming growths in the number of users over the years and to integrate multiple functionalities within a single application for example using the Facebook messenger as a chat platform and at the same time a news browser. Some businesses on the other hand can take advantage of this platform to advertise their products in form of news feeds.

####1.5 References

###2. Overall Description ####2.1 Product Perspective

The chatbot is going to be a news bot that will integrate news into the social life of the Facebook messenger users. That is; one will be able to access news about any events of interest just on his/her screen conveniently in the same way they receive chat messages from friends. This will be done in form of an interaction with the bot by sending messages on topics of interest and in response will be all news findings on the topic.

Integration of business oriented aspects into the chatbot to enable users to know about frequently used products and products being advertised on the chatbot

With the idea to provide news to Facebook messenger users, we intend to implement it within Facebook messenger because of the large numbers of the users of the media who are over nine hundred million. This will therefore make a great audience to the chatbot and the services that it will provide to the users. Given the fact that the chatbot is being built within Facebook messenger, it is typically not self-contained as it will use some privileges from the messenger and Facebook such as the audiences, shelter, and protocols among others.

####2.2 Product Functions

    Subscribe to the news chatbot.
    Receive news.
    Search news by category and keyword.
    Receive news notifications within Facebook messenger.
    Unsubscribe from chatbot.

####A Class diagram showing product relation

diagram/////

####2.3 User Classes and Characteristics
User class 	Frequency of use 	Technical expertise 	Privilege level
User 	Use at any time of choice 	I.T basic knowledge of using computer and mobile applications 	High
Client / customer 	Checking for usability and user requirements 	

    I.T basic knowledge
    System Management skills

	Medium
Developer 	During product testing, implementation and maintenance 	

    Computer application development skills
    Project management skills

	Low

####2.4 Operating Environment

The software will operate specifically in Facebook messenger versions that support chatbots, running on all devices that support Facebook messenger for example mobile hand held devices, laptops and desktop computers.

####2.5 Design and Implementation Constraints

The chatbot will only run in Facebook messenger therefore will accord to all term and conditions of Facebook and Facebook messenger applications plus all government policies that apply to social media applications. It will follow all software development standards in php as a programming language.

####2.6 User Documentation

####2.7 Assumptions and Dependencies

###3. External Interface Requirements ####3.1 User Interfaces

####3.2 Hardware Interfaces

Our chatbot will run on all devices and operating systems that support Facebook messenger that is to say, laptops, desktops, handheld devices among many others. Basically, messages in form of texts and images shall be shared on this chatbot.

Users shall require to be connected to the internet to perform all the desired news searches since the application is internet-based and uses all internet protocols to share data. In addition to the protocols, all information shall be stored and retrieved from the cloud (online servers).

During a chat with the bot, copies of all text and images are stored on both the cloud and the local device storage from which the user can review at a later time even without an internet connection. Synchronization of information between the local storage and the online servers occur whenever there is an internet connection.

####3.3 Software Interfaces

Our chatbot runs within all versions of Facebook messenger application.

####3.4 Communications Interfaces

###4. System Features

####4.1 System Feature 1

####4.1.1 Description and Priority

####4.1.2 Stimulus/Response Sequences

####4.1.3 Functional Requirements

####4.2 System Feature 2 (and so on) ###5. Other Nonfunctional Requirements ####5.1 Performance Requirements

####5.2 Safety Requirements

The chatbot will conform to the phone settings of the user that is to say the font sizes, screen brightness among others. It will have high contrasting colors (colors that do not overshadow one another) to avoid over straining of the users’ sight as they use the chatbot. This will possibly cater for all individual sight issues since every user shall be familiar with their own settings.

####5.3 Security Requirements

As a security precaution, the users of the chatbot shall be assumed to be those of Facebook messenger since it is used within the messenger therefore only those authenticated into Facebook messenger can subscribe to the services of the chatbot. Only subscribed users shall receive notifications and news from the chatbot and at subscription, a user shall be required to verify ownership of the Facebook messenger account with some security questions. On the other hand, all user data shall be stored on Facebook online severs following all restrictions on who accesses which data, why and how.

####5.4 Software Quality Attributes

Below are the intended quality attributes that the software will meet;

    Usability, the product shall exhaust all user requirements as listed and perform all desired tasks.
    Security, precautions on who accesses the user data, how the data is stored, who is allowed to use the chatbot among others shall be considered.
    Learnability, the software will be developed with familiar interfaces to ease learning.
    Availability, always available anytime anywhere.
    Reliability, error alerts and recovery mechanisms in times of component failure.
    Correctness, the software shall perform all required tasks as expected and desired to completion.
    Flexibility, the chatbot shall be easy to integrate within some previous versions of Facebook messenger though not all.
    Safety, all possible safety precautions concerning application use shall be met for example font sizes, color selections, brightness, all to minimize damages that may result from using the chatbot.
    Reusability, the classes, objects, interfaces, subsystems used to develop the chatbot shall be available for reuse in other projects of similar goals just as other already existing ones shall be reused to develop it.
    Maintainability, it will be easy to maintain with clearly joined interfaces and components.
    Portability, the software shall be a cross platform software developed to run on all operating systems that support Facebook messenger for example windows OS, Android OS, Mac OS.
    Scalability, the chatbot shall be able to accommodate increasing numbers of users and increasing amounts of data without affecting performance.

Though all the mentioned attributes shall be met, some shall be given high priorities than others for example;

    scalability has a higher preference than flexibility reason being developing a scalable product is more important than developing one that fits with the existing one.
    Ease of use is preferred to ease of learning because an easy to use product may need less or no training at all.

####5.5 Business Rules

###6. Other Requirements

####Appendix A: Glossary

####Appendix B: Analysis Models

####Appendix C: To Be Determined List

