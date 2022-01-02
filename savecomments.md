# myWebsite
```
		<nav>
    		<ul>
        		<li><a href="/index.html">Home</a></li>
	        	<li><a href="/about.html">About</a></li>
        		<li><a href="/project.html">Project</a></li>
    		</ul>
		</nav>
		<div class="container">
    		<div class="blurb">
        		<h1>Hi there! My name is Steven Yoon</h1>
				<p>I am currently a Sophmore studying Computer Science Student at George Washington University. <a href="/about.html">Read more about my life...</a></p>
			
			Check Out my LinkedIn Page: <a href="https://www.linkedin.com/in/syoon291">LinkedIn Page</a></p>
    		</div>
		</div>
		<footer>
    		<ul>
        		<li><a href="mailto:syoon291@gwu.edu">email</a></li>
        		<li><a href="https://github.com/syoon291">github.com/syoon291</a></li>
			</ul>
		</footer>
```

* Need to work on the linking of pages and fixing the mobile 
    * Mobile, now it works... but you can still scroll over and see it all the way over to the right side of the page...

* Linking of the pages might have to do with the githubw

* Adding events that occur after using the form page on my website

* Making usages for the bottons and links of all these anchor tags

* Update: Fixed the linking between the pages...
	* And the scrolling on the mobile devices

		* Still need to work on the actions from the two forms added on the pages of the website



* moved the php program into here

```
<?php
$name = $_POST['name'];
$visitor_email = $_POST['email'];
$subject = $_POST['subject'];
$message = $_POST['message'];


$email_from = 'info@syoon291.github.io.com';

$email_subject = 'New Form Submission';

$email_body = "User Name: $name.\n".
                "User Email: $visitor_email.\n".
                    "Subject: $subject.\n".
                        "User Message: $message.\n";

$to = 'minorsw70@gmail.com';

$headers = "From: $email_from \r\n";

$headers .= "Reply-To: $visitor_email \r\n";

mail($to,$email_subject,$email_body,$headers);

header("Location: contact.html");

?>
```


