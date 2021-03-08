### Conceptual Exercise

Answer the following questions below:

- What are important differences between Python and JavaScript?
	While JavaScript is a scripting language, Python is an object-oriented programming language


- Given a dictionary like ``{"a": 1, "b": 2}``: , list two ways you
  can try to get a missing key (like "c") *without* your programming
  crashing.
	dict.get()
	dict.getitem()


- What is a unit test?
	A unit test is a way of testing a unit - the smallest piece of code that can be logically isolated in a system.


- What is an integration test?
	Determine if independently developed units of software work correctly when they are connected to each other. 


- What is the role of web application framework, like Flask?
	Provides you with tools, libraries and technologies that allow you to build a web application.


- You can pass information to Flask either as a parameter in a route URL
  (like '/foods/pretzel') or using a URL query param (like
  'foods?type=pretzel'). How might you choose which one is a better fit
  for an application?
	Query parameters are used to sort/filter resources. Path parameters are used to identify a specific resource or resources.


- How do you collect data from a URL placeholder parameter using Flask?
	@app.route('/example/<name>')
	def func(name):
    	print(name)


- How do you collect data from the query string using Flask?
	request.args['data']


- How do you collect data from the body of the request using Flask?
	request.json['data']


- What is a cookie and what kinds of things are they commonly used for?
	Cookies are most commonly used to track website activity. When you visit some sites, the server gives you a cookie that acts as your identification card. 


- What is the session object in Flask?
	session object is used to track the session data which is a dictionary object that contains a key-value pair of the session variables and their associated values.


- What does Flask's `jsonify()` do?
	serializes data to JSON format, wraps it in a Response object with the application/json mimetype.