## ProductChecker

ProductChecker is an online product checking application.

It is designed to check the availability and price of products
available on several online retailers. It features the ability
to track availability and price in realtime and provide historical
graphs. 

It also features the ability to be notified in the case where 
products that were previously not in stock, become in stock. 
This functionality utilizes discord webhooks and requires the user
to configure a discord account and accompanying webhook seperately.


## Windows Installation Instructions
*The following assumes Python 3.9.4 is installed. If you do not have it, it can be found at https://www.python.org/downloads/
- Download the code at the repo either by closing the repo or downloading the zip file. https://github.com/IXISunnyIXI/product-checker
- Extract the contents to a directory of your choosing.
- Using command prompt change to specified directory: cd <enter/full/filepath/of/extracted/contents>
- Create a virtual environment: py -m venv <venv or name of your choice>
- Activate virtual Environment: <venv name>\Scripts\activate.bat
- Install requirements: python -m pip install -r requirements.txt
- Start application: run.py
- Using a web browser, type in the URL bar: http://localhost:5000/register
Enjoy! 


## Documentation

ProductChecker's documentation was primarily created in the form of docstrings from modules, classes, methods, and functions. Pdoc3 was used to autogenerate html pages from the docstrings and hosted on Github pages. Find the docs [HERE](https://ixisunnyixi.github.io/product-checker/).
