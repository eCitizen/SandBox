

------------
Rough Plan: 
zSuccess Metrics - 
Boundary Conditions  
Things that could complicate the plan  
Units and value of success have to outweigh the entropy  
Whatever we do, cannot do harm  
Personal data information access/developement  
Fields of ID  
Address  
Phone  
Web 2.0 acct system  
High value access  
Descriptive and Predictive Model  
Vectors and Params  
Params  
Simple sources  
Glean from phone data  
By permission from 3rd parties  
Senario and Use Case   
In all  
People  
Action  
Data   
System    
Senario  
Sports   
People 	 
User  
Circulation/Marketing   
3rd party   
Partners   
NESN  
Other users  
Celebrities / Brand Names 	  
Actions/Interactions  
Data  
Systems  
Services   
Apps  
Traffic  
City and State  
Hubway  
MBTA  
Car  
Actions  
Traffic  
Where is good to go?   
Data  
Traffic Data  
Model to include vectors   
Where were that last Tuesday, will tell you where they will be next Tuesday 

Boston Globe to build a mobile tool that explores the use of data collection for personal experience  
	For iPhone system  
	With account system (to be built)  
	Utilize accounts inherent capability to use OpenID Connect  
	Augmentable by design with ANY OAuth2 App or Service 
	
	Two outcomes:   
  	1. Build and test a model (w/vectors and parameters) of users to validate success metrics (value of personalization)   
		2. Demonstrate/evaluate web 2.0 (OAuth2/REST open architecture) end-point based design patterns so you can have an agile re-purposable infrastructure and pivot to other business models  / opportunities quick/easy (like a ballerina) 
			Identity system is an object with standard inputs and outputs 




=========================
some food for thought:


# Concept: HyperPersonalNews

Could use identity from user account with the app to - by permission - access profile attributes to tailor, customize or recommend personalization based on a significant number of individual identity anchor points (see the following identity “attributes” as examples of the types of personalization data each user could authorize access to see so the app can customize news based on the address of the user, or custom attributes can be used as well, including to their “profile pages” on Facebook, LinkedIn, GooglePlus, etc so the key words in a large range of additional personal information can be harvested.  
 
It is also possible to use a non-globe service where users can “store” their profile and/or identity attribute information.  In this case, the best practice would be to use a “personal data store” aka PDS.  In this way, the users maintain control over sharing preferences and which apps or services are granted permission.  For this capability, we could possibly set up a service for the app with our Media Lab open source pds and connect it to the App’s user accounts via OpenID Connect “user end-points”.  Check out: http://openpds.media.mit.edu/ 


_____________
# Notes

## Raw Notes from Arek Hangout Dec 12, 2013

Arek:

PoC on the MODEL for predictive analytics and personal identity by permission

* perhaps at the LogIn (with fb) also have option to download the app
* use openPDS on the background
* Do a test to see which is better:
 - one set with fb posts/topography 
 - other set with geo/location
 - other set with id attributes

* Traffic:
 -
 -
 -

* Approach: prove the personalization: build a recommendation engine quickly
 - try FB (people you know/like on fb ALSO read X content)
 - try Personal Data and see if those recommendation are better (LOCATION: the place you frequent!)

* PoC would be to establish whether and to what extent it does work:
 - the 
- value is that we can ADD more data to get higher relevance 
- value is also that we are doing this in a very privacy enhancing way!

Arek Back 
* February 10th - 2 weeks
* TBD

-----
TRUST is an issue:
* The Washington Post 
