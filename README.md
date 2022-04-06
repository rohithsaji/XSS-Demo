Name: Rohith Saji
RollNo: 181CO143

Follow the instructions below:

- Run npm install to install all requires packages.
- Run the local web server using node server.js.
- Server should be running at localhost:3000
- Check the attached report for the demo.
- Send the malicious inputs like this:
	- For Eg: To display the user cookie on the site the following code should be sent:
	<img src="does-not-exist" onerror="alert(\'hi!\')">
	- To send this run the following on the browser console:

	encodeURIComponent('<img src="does-not-exist" onerror="alert(\'hi!\')">');

	OUTPUT: %3Cimg%20src%3D%22does-not-exist%22%20onerror%3D%22alert('hi!')%22%3E

	- And attach the output of the above as the query in the url of the webpage as the following:
	http://localhost:3000/?q=%3Cimg%20src%3D%22does-not-exist%22%20onerror%3D%22alert('hi!')%22%3E



