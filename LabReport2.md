# Lab Report Two
---
Author: Sean Tran 

PID: A16045509

## Part 1 StringServer Webserver
* This is the code that runs String Server
* String Server takes in a request to display information on the page.
* Requests are kept track in a single string displayed on the page
![Image](1.29.0.PNG)
* In the screenshot below, multiple methods were called to display the information shown
* The first method called was StringServer's main method that started the actually server. The method required one argument which was the port (I used port 4000. The method checks if a port was given, if there was one then it will try to run the server on that port else it would give a missing port error.
* The second method called was StringServer's handleRequest method that takes in a URI. It then parses the url path and checks if there was a proper request ("/add-message") and stores the information after the "=" into a string array called parameters. The method then parses through parameters and stores the String data into the answer string. The String answer is a instance variable so it lasts as long the server is running on that instance. Answer stores all the data in request. So as the user adds more requests, the requests are stored in answer and displayed on the page.
![Image](1.29.1.PNG)
* In the screenshot below, the method StringServer's handleRequest method is run. This is done when the user edits the url from http://localhost:4000/add-message?s=Hello to http://localhost:4000/add-message?s=How are you. When this method is called, it parses the url to find the string data that occurs after the "=" and stores it in answer. Answer is then returned and displayed on the page.
![Image](1.29.2.PNG)

## Part 2 Explaining a bug
* The code block below is an example of failure-inducing input for the reverseInPlace method
```json
{
   	@Test 
	public void testReverseInPlace2() {
   	int[] input1 = { 1,2,3 };
   	ArrayExamples.reverseInPlace(input1);
  	 assertArrayEquals(new int[]{ 3,2,1 }, input1);
	}
}
```

* The code block below is an example of non-failure-inducing input for the reverseInPlace method
```json
{
	@Test 
	public void testReverseInPlace() {
    	int[] input1 = { 3 };
    	ArrayExamples.reverseInPlace(input1);
    	assertArrayEquals(new int[]{ 3 }, input1);
	}
}
```
* This is the symptom as the output of runnign the tests described above.
