# Introduction

This is the instructions page for our 2013 Forum EPFL Workshop, "RESTful applications with Apache Sling and Adobe CRX". 

The workshop takes place on October 16th 2013 at EPFL forum, http://forum.epfl.ch/ has the forum information, and students should have
received info about how to sign up.

Our goal for this workshop is to meet students who might be interested in doing an internship at Adobe Basel, and/or in being hired there. Getting to know you and how you work is an important part of our selection process, so you maximize your chances of getting an interview with us by taking part in the workshop.

To keep things open-ended and fun, instead of giving you strict instructions about what to do during the 3-hour workshop we will ask you to imagine and implement something cool on top of an existing [Apache Sling](http://sling.apache.org) sample application. Sling is the core of our flagship CQ/AEM content management and digital marketing system, but in itself is an open source project which makes it easier to let you work on it at the workshop.

The list below suggests a number of extensions and improvements that you could implement on top of the existing Slingbucks sample applicaton. Feel free to suggest your own value-adding ideas at the workshop, if you see something else that's fun and useful.

# Instructions

1. Clone the [Apache Sling](https://sling.apache.org) project from its Github mirror at https://github.com/apache/sling
2. Build the project with the Maven command line tool, following [build instructions](http://sling.apache.org/documentation/development/getting-and-building-sling.html)
3. Start the Sling runnable jar
4. Sling contains a sample called [Slingbucks](https://github.com/apache/sling/tree/trunk/samples/slingbucks), simple coffee-ordering app  
   Install the sample following the README instructions and start playing with it
5. Code your extension/improvement and deliver it from your own GitHub repository or similar public location.

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

## Add new features

For instance:

* **Ability to enter discount vouchers**  
  Administrator generates vouchers, each with unique code, and customer can enter it when ordering.  
The application invalidates the voucher when it's used.
* **Generate human readable but hard-to-guess order IDs**  
  Current application currently generates a long hexadecimal string, which no one can memorize.  
  This allows a minimal security of orders.  
  One idea could be to generate meaningful but hard-to-guess strings, like for instance PINKRABBIT13, FERRARIF40, etc.
