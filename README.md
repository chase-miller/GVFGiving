# GVFGiving
Banking Integration for GVF to take One-Time and Recurring Tithes and Offerings

# Introduction
The purpose of the is project is to integrate the Dwolla API with the Squarespace GVF page.  Once this is complete I intend to generalize this and offer it to anyone looking to collect Dwolla payments on their websites

# Developer Setup
* Clone this repository 
``` git clone https://github.com/JasonvanBrackel/GVFGiving.git```
* Install the most recent version of [Node.js](https://nodejs.org).  The LTS version is fine as well.
* Install jasmine for testing via NPM (-g installs it globally, feel free to omit as you see fit.)
``` npm install -g jasmine ```
* Install the Dwolla SDK via NPM
``` npm install dwolla-v2 ```