info
====

This project is made in the purpose of getiing a possibility to build an interface to generate an **integrated info** from all [GOOGLE CLOUDS](https://cloud.google.com/developers/) including *[API's](https://developers.google.com/apis-explorer/#p/), [Application API](https://developers.google.com/google-apps/app-apis), [Application Sripts](https://developers.google.com/apps-script/), [Application Engine](https://developers.google.com/appengine/); [Cloud Storage](https://developers.google.com/storage/), [Cloud Datastore](https://developers.google.com/datastore/), [Cloud SQL](https://developers.google.com/cloud-sql/)* etc. 

It aim to have the access and running all available program language like *Python, Java, PHP, Go* with possible also *Scala and Ruby* and run them in the **same time** in to a SINGLE PAGE using a SINGLE DOMAIN without even need any sub domains! 

Thanks to Google for bring this possibility to the world and making it happen.


##Languange Structure
In order to run all program language in the same time then they are configurated as below:
- **Python** is used to access all images with an access to any Image Manipulation run from Phyton Frame such as *Django* and compiled as 'images module'.
- **Java** is used to access all javascript file with an access to Servlet Application run from Java / Javascript Framework such as *GWT (Google Web Toolkit)* and compiled as 'scripts module'.
- **PHP** is used to generate the front page run from PHP Framework such as *Zend, Kohana* etc and collected alltogether in a 'default module'.
- **Go** is used to access any application that Support for *Docker images* in Google Cloud Platform with an intention to have a possibility to run and gain access a global structure application that run in other languages such as *Perl, C, C++, etc*. 


##Application Structure
Having possibility to run all language then we have no more resistant to gain a **simultaneously** access to any other [GOOGLE PRODUCT](https://developers.google.com/products/) including *Google Talk, Google Play Androids, Google Maps, Google Drive, Google Analytics, Google AdWords, Google Wallet, Youtube, etc* which also open an access to more **widely and global** application such as *[Compute Engine](https://developers.google.com/compute/) and [Big Query](https://developers.google.com/bigquery/)*.

Find More of Google Products [here](http://en.wikipedia.org/wiki/Google_Services#Mobile_applications).

front page (generated by Php)
- images directory (access by Phyton)
- sripts directory (access by Java)
- styles directory (access by Go)
- plug-ins directory (where Python, Java, Php, and Go codes reside)

The application development is limited until gain the access only means once the communication to a targeted product is successfully provided then no further development will be made unless a necessary improvement required. This will also covering the seletion to the *most reliable code* using most appropriated program language to do the job. 


##Documentation Structure
As Google has made a nice and beautifull documentantion for each of their product then the documentation of this project will be made as simple as possible in only to expalin a specific task on how to make the code running and succesfully gain the access to each Google Product. The link to develop in deeper will be provided in the discussed section.

Building and Test is being carried out. As a sample for online demo that create a simple page applying the above scheme using Google App Engine with the Google Cloud Storage as well also use the following Google Products as below:

- Google AdWords to promote the front page
- Google Analitycs to measure the pageview
- Google Channel for online communication

If you like to see the demo, it can be visited [here](http://tophyips.info)

**The following development is on the way**: 
- Build the Front Page using PHP Frame Work (Zend and Kohana)
- Generate Script Manipulation to Run Java Servlet using GWT (Google Web Toolkit)

**On Going Development**:
- Generate Image Manipulation to Run Python FrameWorks such as Django
- Generate Styles Manipulation to Go Framework using Kubernetess/Docker

Feel free to try your hand at building other formats, any discusiion will be opened later once the application is meeting the most target as described above.
