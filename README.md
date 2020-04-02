# groupSilver

Fighter Portal page created by Nicholas Nwanochie,Sean Page, Steven Johnson, Kazim Shabbir

	This website has three main features. They include users being able to find and purchase tickets to various fighting events via TicketMaster API integrated into the website. It allows for the finding of local gyms in the Houston area via Google maps API. Lastly it features an self updating ticker on the main page saying various events in all sports in real time.
Both TicketMaster and Google API’s were both attained by use of a API key and further implementation in the JS of the website. The TicketMaster API listed various fighting events in real time while also linking users to their site for ticket purchase. To make the API more user friendly the fight dates where integrated into a calendar using CSS and JavaScript. 
	The Google API was used to specify the location of fighting gyms, and we later shortened that list down to gyms features 4 stars or more. We used flat-icons to replace the typical icons use by Google to signify a location. Lastly we add links to the gyms along with phone numbers to make access easier.
	Our real-time ticker was made using key-frames and an API for sports to bring a running list of main events in all main American sports. The list items are also links sending you to their respective article sites. It was styled using CSS and flex-box to position correctly.
	Our fight portal page was made as an interactive part of the site using python to randomly pick the victor of two UFC opponents. 

						Challenges  faced
The main challenges faced was implementation of the Python code and establishing the Google API.



						Solutions
The Python for  the site had to be used in a way that will detect the click event of the battle button and use a self made algorithm to select the victor of the battle. This was handled using similar code for each fighting via class super functions and making the algorithm with based on certain factors turned into numbers such as age, wins, and losses. This was outside the scope of our project and will be implemented during the fullstack project portion.
The google API was handled by first getting the key from Google, which required us to sign in for an account. After that portion was simply got the longitude and latitude of the gym locations and passed them into our JS code accompanying our API
