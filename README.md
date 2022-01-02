# Update Notice on this repo...
* Moved all the data from this repo into my github.io








# Notes and Comments While Testing
* Link to my page: https://syoon291.github.io/myWebsite/

* Here are some of my versions and comments:

## Citing my work
* link for the place where I credit the program: 
* https://www.youtube.com/watch?v=oYRda7UtuhA&list=WL&index=1&t=2543s



### Need to work on next...

* Need to work on the linking of pages and fixing the mobile 
    * Mobile, now it works... but you can still scroll over and see it all the way over to the right side of the page...

* Linking of the pages might have to do with the githubw

* Adding events that occur after using the form page on my website

* Making usages for the bottons and links of all these anchor tags

* Update: Fixed the linking between the pages...
	* And the scrolling on the mobile devices

		* Still need to work on the actions from the two forms added on the pages of the website


* Update... 
    * need to work on the some aspect of the icons
    * make some of the icons link to some websites upon clicking on them?
        * maybe adding some anchor tags and adding links to the icons?

* Update: 
    * The sending an email using php doesn't seem to be working 
    * maybe integrating a google form into the website just like google maps?
        * look into that, just a simple google search will probably be able to find some exmaple 
            * or some youtube video on it 


```
<!DOCTYPE html>
<html>
	<head>
		<title>Steven's Projects :D</title>
				<!-- link to main stylesheet -->
		<link rel="stylesheet" type="text/css" href="/css/main.css">
	</head>
	<body>
		<nav>
    		<ul>
        		<li><a href="index.html">HOME</a></li>
				<li><a href="about.html">ABOUT</a></li>
				<li><a href="project.html">PROJECT</a></li>
				<li><a href="course.html">COURSE</a></li>
				<li><a href="contact.html">CONTACT</a></li>
    		</ul>
		</nav>
		<div class="container">
    		<div class="blurb">
        		<h1>Projects :D</h1>
				<h3>Sophmore Year Courses List:</h3>
				    <ul>
					<h4>Software Engineering (CSCI 2113) Projects:<h4>
					<ul>
					    <li>Boggle Solver (C Programming Language)
					    <li>Creature Chaser on a Dot Plotter (Java Programming Language)
					    <li>Slack GUI (Java Programming Language)
					</ul>

					<h4>Computer Architecture I (CSCI 2461)
					<ul>
					    <li>Encryption Decrpytion (LC3 Assembly Programming)
						<p> Asking the user for input E or D or X. Depending on the user input, the program will branch to either encrpytion or decryption or exit, respectfully. To make sure the user inputs a correct option, the programs checks to see if the its one of the three, otherwise it loops asking the user to enter again. The inputted choice is not shown on the console. Upon entering E, the program will ask the user for a key. If the user inputs an incorrect key, the program will ask the user to re-enter a valid key. Once entering a valid key, the program will prompt for a message to be encrypted. Once entering in the correct message, the program loops back to asking the user to choose E,D, or X. For decryption, the program asks for a valid key and returns back to prompting. Lastly, the only way for the user to exit the program is to enter E. </p>
					    <li>Search Engine W/HashMaps (C Programming Language)
						<p> The program is ran through the terminal. Upon running the program, the program will prompt the user to enter the number of buckets for the hashmap. Once creating the hashmap with the correct number of buckets, the program will input each word from every document from a test folder using glob. Once inputting all the words into the hashmap, the program then asks the user for a search query. With the inputted query, the program then ranks and prints out the documents that the words are located within to the terminal. Additionally, the program creates a separate text file with the ranked documents in order and the scores associated with it. Within the program, the only way to exit is to input X as the search query. Otherwise, the program will look for the search query within the documents and rank them. </p>
						<p> The structure of the hashmap used for the storing the words is unique. With each bucket is a linked list. Within the first linked list, each node points to the next node of the list. Additionally, each node in the first linked lists also points to another linked list which is to store the document Nodes.</p>    
					</ul>
    		</div><!-- /.blurb -->
		</div><!-- /.container -->
		<footer>
    		<ul>
        		<li><a href="mailto:syoon291@gwu.edu">email</a></li>
        		<li><a href="https://github.com/syoon291">github.com/syoon291</a></li>
			</ul>
		</footer>
	</body>
</html>

```
