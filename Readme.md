#**Web Data Management phase 3 **  *(atul.konaje@mavs.uta.edu)*    

##### *node.js , Angular.js*
#     
#   

### *Installation* :
 - Unzip the  **axk5198-project-phase3.zip**
         unzip axk5198-project-phase3.zip
		
- Change to the unzipped directory
        cd axk5198_wdmphase3
		
- Run the below command to install the package dependencies
        npm install

- A folder called **node_modules** gets generated with the dependent packages after the above command is successfully executed.

 # **Usage**
  **Insertion of data into database**
- Run the below commands to insert the data from JSON file into MongoDB . Once the insertion is done , console will display that records are successfuly inserted.
        node Mongo.js

- After the insertion of data into database,Start the nodejs application,type the below code on the command prompt
        node server_side.js
- Open a browser ***Google chrome / Mozilla ***  *(Dont use IE,All Animations wont work on IE) And Internet connection should be available for CDN libraries* .           Visit http://localhost:3000

-The webpage window will show a button, click to start.

##1.    What aspect of the implementation did you find easy, if any, and why?

*  ##### *I found the insertion of JSON data into the MongoDB database easy,as the JSON format is more friendly with MongoDB and I just had to parse the json and insert it.*

*  ##### *Express library of nodejs made routing the AJAX calls from client easier with lessser code overhead*
*  ##### *The voracious styling options of CSS3 provided me lot for animation features to play with.*
*  ##### *The d3.js library functions made dynamic DOM modification easy with their library functions *

##2. What aspect of the implementation did you find hard, if any, and why?
* ##### *Each time the server makes an AJAX request, the server has to get a new record from the Mongo database. Since the calls were asynhronous had to find a strategy to retrieve unique record each time. So passed parameter in the request  to fetch a new record for each request.*
* #####*I had to put effort in Displaying only 20 records at a time. Used modulo to loop on first 20 table data elements*
*  ##### *node.js being non-blocking its asynchronous. Had to make use of the call back functions efficiently for the program logic to run in the order I required*

##3. If you were to use these technologies professionally, what would be your biggest concern?
* ##### *I would have found the usage callback functions for more complex logic cumbersome. The call back functionality of the node.js makes the code readability little function and even the code development little tuff  to some extent.*
* ##### *Will need a complete understanding of library functions of D3.js for more complex animations in data driven documents.It also involves a certain amount of knowledge and expertise in programming computer graphics  *

 




  

