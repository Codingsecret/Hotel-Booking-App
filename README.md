# Hotel-Booking-App
Hotel Booking App on PHP

How to run the Hotel Booking webiste file in XAMPP (4 Easy Steps)

XAMPP is a popular open-source cross-platform web server solution stack package, which consists mainly of the Apache HTTP Server, MySQL database, and interpreters for scripts written in the PHP and Perl programming languages.

It's perfect for testing HTML, PHP and other types of web pages locally.

Here is a step-by-step guide to run an HTML file in XAMPP:
_________________________________________________________________________________________________________________________________________________________

**Step 1: Install XAMPP**
Visit the Apache Friends website to download XAMPP: [https://www.apachefriends.org/index.html](https://www.apachefriends.org/index.html)

Choose the version of XAMPP appropriate for your operating system (Windows, Linux, or Mac).

Click on the downloaded file to open the installer.

Follow the instructions on the installer, accepting default settings where you're unsure.
________________________________________________________________________________________________________________________

**Step 2: Start XAMPP**
Once XAMPP is installed, locate the XAMPP Control Panel on your computer. On Windows, you can search for 'XAMPP' in your Start menu; on Mac, you can find it in your Applications folder.

Open the XAMPP Control Panel.

Click the 'Start' button next to 'Apache'. This starts your local server. If MySQL is also started, you can stop it for now as it's not required to run HTML files.
__________________________________________________________________________________________________________________________________________________________________________________

**Step 3: Place Your HTML File in the Right Folder**
Locate the 'htdocs' folder inside your XAMPP installation directory. By default, it is typically C:\xampp\htdocs on Windows, and /Applications/XAMPP/xamppfiles/htdocs on Mac.

Place your HTML file in the 'htdocs' folder. You can either copy and paste the file there, or you can create a new folder in 'htdocs' and place the file in that folder. For example, you could create a folder called 'hotelbooking' and place 'index.html' inside 'public'.
____________________________________________________________________________________________________________________________________________________________________________________
**Step 4: Access Your HTML File**
Open a web browser of your choice.

In the address bar, type localhost/ followed by the path to your HTML file in the 'hotelbooking' folder. 'index.html' is in a folder named 'public', you would type localhost/hotelbooking/public

Press Enter. Your HTML file should display in your web browser, being served by your local XAMPP server.

That's all you need to do to run an HTML file on XAMPP! Remember, you can use this same method to test PHP files or other types of web content on your local server.
___________________________________________________________________________________________________________________________________________________________________________________________________________
**Best Practices -**

Getting HTML to run on your local browser is just the first steps. You will likely need to know the following for a better development learning journey-

**1. File Organization:**
It's good practice to create separate folders within the htdocs directory for each project you work on. This keeps your projects organized and prevents conflicts between different websites you might be testing locally.

**2. Error Troubleshooting:**
If your HTML file isn't displaying correctly, there could be several reasons. Some common ones include:

**Syntax errors in your HTML code**

Incorrect file path in the browser address bar

Apache not running in the XAMPP Control Panel

Inspect your HTML code carefully and make sure Apache is running. If you see an error message in your browser, it can provide clues about what's going wrong.

**3. Understanding Ports:**
By default, XAMPP uses port 80 for the Apache HTTP server. If you have another application using port 80, Apache may not start correctly. In the XAMPP Control Panel, you can change the port Apache uses if necessary.

**4. Using HTTPS:**
XAMPP also comes with support for SSL/TLS, enabling you to use HTTPS with your local websites. This can be useful if you're testing functionality that requires HTTPS.

**5. Database Integration:**
While you don't need a database to run HTML files, you may want to use one if you're also testing PHP scripts or other back-end functionality. XAMPP includes MySQL and phpMyAdmin for this purpose. You can start MySQL from the XAMPP Control Panel and access phpMyAdmin by navigating to localhost/phpmyadmin in your web browser.

**6. XAMPP's Security:**
Since XAMPP is designed to be an easy-to-use development environment, it's not secure for use as a live, public-facing web server. If you want to host a website publicly, it's recommended to use a dedicated hosting provider or a cloud service like AWS, Google Cloud, or Azure, which are designed with security in mind.

**7. Updating XAMPP:**
Always keep your XAMPP installation updated. Each new release includes important security patches and updated versions of the Apache HTTP Server, PHP, and MySQL.

However, be cautious about updates if you're in the middle of a project - they could potentially break your existing code. Test your websites thoroughly after any update.

I hope you found this useful. Let me know if you run into troubles or get any error message.
