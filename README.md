# Forex Converter
Foreign currency converter app built using python and flask. No JS. Uses forex-python to retrieve latest exchange rates.  
<img width=20% src="https://www.jorgeweiss.com/static/forexpic.png">


Ideally this application would be made wish AJAX to create a better UX but I sought out to create a web app without a client-side script file. Although it was possible to create the application without the script file, page redirects were necessary without the AJAX functionality.

## technology used
* Open source [forex-python](https://github.com/MicroPyramid/forex-python) was used to retrieve latest exchange rates.
* Flask (lightweight python framework) was used to handle routes and make server-side API calls using the `requests` dependency. 
