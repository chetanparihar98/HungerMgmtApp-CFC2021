# Hunger Management App
**Theme:** Zero Hunger 

This repository discusses a solution to provide a platform to people to share information regarding free/inexpensive food-drives conducted by Governments, Private Firms, NGOs, and other such authorities through request-based and tokenized volunteer-based system.
			 
# Contents
	
  * [Submission or project name](#hunger-management-app)
	* [Contents](#contents)
	* [Short Description](#short-description)
	* [Long Description](#long-description)
		* Understanding the Scenarios
		* Technology as a platform
		* The solution
	* [The Architecture](#the-architecture)
	* [Video Presentation](#video-presentation)
	* [Project Roadmap](#project-roadmap)
	* [Getting Started with the app](#getting-started-with-the-app)
		* Readme
		* App Apk
		* Android Build Files
		* Node.js Rest Services App and Files
		* Mongo Atlas database
		* 2Factor.in OTP Service files
	* [Built with](#built-with)
		* Android Studio 
		* Mongo DB Atlas
		* IBM CLoud foundry
		* Node.js & NPM
		* 2Factor.in OTP Service 
	* [Working Team](#working-team) 
		
# Short Description

Informative Platform about Food Drives along with Food Donation & Volunteer Mechanism.  

# Long Description
* **Understanding the Scenarios**
	* **Scenario 1:** 

	In India, during the pandemic, many people were facing the problem of starving due to less availability of food. In some locations, governments and private firms were trying     to distribute free food to such people, but the information was not available to each and every person who needs it. Also, due to restrictions of limited movement and the       special care needed, these authorities cannot distribute food packets to individuals in a distributed manner too. A platform, dedicated to availability of free food (NGO         drives, individual serves or Government/Private Food Drives) in one’s locality will enable him to feed himself and share the information. As the pandemic isn’t over yet, and     consequences are yet to be fully measured, starvation and supply of [free] food to such needful people will become a greater challenge.
	
	* **Scenario 2:**
	
  In times out of the pandemic, people may still be able to use services of the platform but in a different manner. But let’s first understand the issues
      
     * In such times, co-ordinated free food drives won’t be available. Rather, it will be handled by lower authorities and Non-Profit/Non-Governmental Organizations. These may or may not be free, but it will definitely be in-expensive than other options available.
     * Not able to locate a food drive, people should be able to create requests of need which can be passed to such organizations. This data can be analysed and will enable organizations to conduct food drives with a more real-time data-driven policy. 
     * Although the smartphone base is going to grow, but there will be people who can’t afford them. Such people will be taken care by a tokenized volunteer-based system. This will earn rewards for the volunteer who routes the people to such organizations through a token for reward references.

* **Technology as a Platform**

Through technology, we can create platforms to integrate all this information into a single structure. Also, we can co-ordinate activities related to such operations using volunteer base.
		
* **The Solution**
		
The solution consists of a Mobile Application, to give people a platform to host food services and also accumulate volunteers for targeted NGO operations to reach the most remote disabled User.

  * **Solution Platform Components**
	
    * **DASHBOARD** – A common access point for all services offered
		
    * **MAPPING OF FOOD SPOTS** – A simple UI conveying information about all the free-food spots/drives available in the vicinity of the user. 
		
    * **BECOME AN ORGANIZATION** – A section to use when a particular user wants to upgrade himself to an organizational entity (to create a food spot/drive OR Register for Volunteer based operations)
		
    * **BECOME A VOLUNTEER** – A section to apply for volunteer work to earn reward points based on the necessity.
		
    * **DONATE FOOD** – A section to donate food or create a food surplus request for real-time data analysis.

# The Architecture 

![Architectural Diagram](https://user-images.githubusercontent.com/32700922/122092330-6a748680-ce27-11eb-894e-5effc0289876.jpg)
	
* The user will be able to access the App DASHBOARD via Login (Mobile Number and OTP based registration)

* The DASHBOARD will present mainly 4 sections to every user viz. MAPPING OF FOOD SPOTS, BECOME AN ORGANIZATION, BECOME A VOLUNTEER and DONATE FOOD

* All components interact with the Node.js Rest Services hosted on the IBM Cloud Foundry Environment via REST API Calls.

* The Node.js Application is in turn synchronized with the MongoDB Altas for Database integration and an OTP Service for Token forwarding.
	
# Video Presentation

[<img src="http://img.youtube.com/vi/Z80UNwXPQJQ/0.jpg" width="75%" height="65%">](http://www.youtube.com/watch?v=Z80UNwXPQJQ "Video Title")

# Project Roadmap

We are going to use a Rapid Development Model (rolling out updates over different periods of time) 

* **June 2021:** Integrate LOGIN and MAPPING OF FOOD SPOTS Modules.

* **July 2021:** Add BECOME AN ORGANIZATION and DONATE FOOD Modules.

* **August 2021:** Add BECOME A VOLUNTEER module and publish the app for survey.

* **September 2021:** Servey based Results leading to optimization in the 4 Modules and Bug Fixes.

* **October 2021:** Final Publish and post-publish module planning.
		
# Getting Started with the app

The following two repositories contain the project specific files for building the APK. 
* The Android Files contain the UI Activities (Login (along with OTP verification), Signup and Food Spots display by fetching results from the MongoDB Atlas) and the OTP Verification and Authorization Modules
* The Node.js Files contains all the necessary modules and packages to build and run a node.js rest services app on the IBM Cloud Foundry Environment. 
* Other Application modules (Become Org, Volunteer and Donate food) are yet to be implemented.

Click on the below links to re-direct to the repositories related to the project. 
		
[Android Application Project Files](https://github.com/chetanparihar98/CFC-APP)

[Node.js App Files](https://github.com/chetanparihar98/CFC21-RestApi)
	
# Built with 

* **Android Studio:** Android Studio is the official integrated development environment for Google's Android operating system, built on JetBrains' IntelliJ IDEA software and designed specifically for Android development. 

* **Mongo DB Atlas:** MongoDB Atlas is the global cloud database service for modern applications.

* **Node.js & NPM:** Node.js is an open-source, cross-platform, back-end JavaScript runtime environment that runs on the V8 engine and executes JavaScript code outside a web browser.

* **2Factor.in OTP Service:** 2Factor (Solv technologies) is popularly known as the best & reliable bulk sms gateway/service provider in India

* **IBM Cloud Services included:**
	
	* **IBM CLoud foundry:** Cloud Foundry is an open source, platform-as-a-service (PaaS) on IBM Cloud
	
	* **IBM Cloudant Service:** (invoked by Cloud Foundry Environment)

# Working Team
		
* **Chetan Parihar**, Idea Analysis & Documentation, Refining and Technical Support

* **Adithya A N**, Android Application Developer and Server Deployment
		
* **Vivek Jadhav**, Node.js & REST Services Developer

* **Prateek Hadawale**, Node.js & REST Services Developer

* **Rahul Bindrani**, Node.js & Web Services Developer
