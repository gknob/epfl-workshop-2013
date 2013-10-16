# Introduction

This is the instructions page for our 2013 Forum EPFL Workshop, "RESTful applications with Apache Sling and Adobe CRX". 

The workshop takes place on October 16th 2013 at EPFL forum, http://forum.epfl.ch/ has the forum information, and students should have
received info about how to sign up.

Our goal for this workshop is to meet students who might be interested in doing an internship at Adobe Basel, and/or in being hired there. Getting to know you and how you work is an important part of our selection process, so you maximize your chances of getting an interview with us by taking part in the workshop.

To keep things open-ended and fun, instead of giving you strict instructions about what to do during the 3-hour workshop we will ask you to imagine and implement something cool on top of an existing [Apache Sling](http://sling.apache.org) sample application. Sling is the core of our flagship CQ/AEM content management and digital marketing system, but in itself is an open source project which makes it easier to let you work on it at the workshop.

The list below suggests a number of extensions and improvements that you could implement on top of the existing Slingbucks sample applicaton. Feel free to suggest your own value-adding ideas at the workshop, if you see something else that's fun and useful.

# Instructions

We expect you to come to the workshop ready with a basic setup where you have the Slingbucks sample running on a Sling instance
and you understand how to make changes to the application.

## Before the workshop

1. Clone the [Apache Sling](https://sling.apache.org) project from its Github mirror at https://github.com/apache/sling
2. Build the project with the Maven command line tool, following [build instructions](http://sling.apache.org/documentation/development/getting-and-building-sling.html)
3. Start the Sling runnable jar
4. Sling contains a sample called [Slingbucks](https://github.com/apache/sling/tree/trunk/samples/slingbucks), simple coffee-ordering app  
   Install the sample following the README instructions and start playing with it.

If you have questions about this, feel free to ask on the Sling users mailing list, see http://sling.apache.org/project-information.html#mailing-lists
   
## At the workshop

5. Discuss your plans with us, what you'd like to implement and how.   
6. Code your extension/improvement and deliver it from your own GitHub repository or similar public location.
7. Submit a pull request for this page so that we can add the URL of your work below under "participant's repositories".

# Potential workshop activities

Depending on your interest, you are free to focus on one of the following topics.

## Tests

From [Testing Sling-based applications](http://sling.apache.org/documentation/tutorials-how-tos/testing-sling-based-applications.html) documentation page:  
Automated testing of OSGi components and services can be challenging, as many of them depend on other services that must be present or simulated for testing. There are various approaches to test Sling itself, and introduces a number of tools that can help testing OSGi and HTTP-based applications.

You can decide to write tests of any kind.

## Make a mobile version

Using a [PhoneGap free plan](https://build.phonegap.com/) or any other suitable technology, you will be able to implement a mobile version of Slingbucks.
    
## Make it look nice(r)

Current UI is very basic, but it can be improved using any tool(s) of your choice.

Feel free to create a fantastic user experience for this simple app, and blow our socks off...

## Add new features

For instance:

* **Ability to enter discount vouchers**  
  Administrator generates vouchers, each with unique code, and customer can enter it when ordering.  
The application invalidates the voucher when it's used.
* **Generate human readable but hard-to-guess order IDs**  
  The application currently generates a long hexadecimal string as a coffee order ID, which no one can memorize.  
  The goal is to implement a simple security by obscurity, which is good enough in this case but can be made nicer using
  more readable/speakable IDs.
  Hard-to-guess readable IDs can be generate by combining common words in unusual ways, like for instance PINKRABBIT13, FERRARIF40, etc.

## Participant's repositories

* [Nicolas Voirol](https://github.com/samarion/sling)
* [Kim Miji](https://github.com/itrustyou777/sling)
* [Thang Chi Duong](https://github.com/vic4ever/sling)
* [The Anh Nguyen](https://github.com/ntas1310/sling.git)
* [Aniruddha Loya](https://github.com/aniruddha-loya/sling)
