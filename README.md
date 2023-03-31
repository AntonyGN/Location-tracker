# Location-tracker
Location Tracker is a simple application that allows you to track the country of any phone number using the phone number's country code. It is written in Python and uses the ```pycountry``` and ```phone_iso3166``` libraries for looking up country information based on the phone number.

## To use this code in Jupyter Notebook, follow these steps:

1. Install the required libraries: ```pycountry``` and ```phone_iso3166```. You can do this using ```pip``` by running ```pip install pycountry phone-iso3166``` in a code cell.

2. Copy the code for the Location Tracker application into a code cell in Jupyter Notebook.

3. Run the code cell to define the ```Location_Tracker``` class and create an instance of it called ```MyApp```.

4. Run the next cell which calls ```PhoneTracker.mainloop()``` to run the ```Tkinter``` event loop and display the application.

5. Enter a phone number into the application's input field and click the ```Track Country``` button. The country associated with the phone number's country code will be displayed in the application's output label.


## Here's a breakdown of the code:

1. Import the required libraries: ```json```, ```pycountry```, ```Tkinter```, and ```phone_iso3166```.

2. Define a class called ```Location_Tracker``` that represents the application. In the ```init()``` method, create the application window and its widgets (a label, an entry field for the phone number, a button to track the country, and a label to display the output).

3. Define a method called ```Track_location()``` that is called when the ```Track Country``` button is clicked. This method retrieves the phone number entered by the user, looks up the corresponding country using ```pycountry``` and ```phone_iso3166``` libraries, and updates the output label with the name of the country.

4. Define an instance of the ```Location_Tracker``` class called ```MyApp``` and run the ```mainloop()``` method of the ```Tkinter``` module to start the application's event loop.

5. When the ```Track Country``` button is clicked, the ```Track_location()``` method is called, which retrieves the phone number entered by the user, looks up the corresponding country using ```pycountry``` and ```phone_iso3166``` libraries, and updates the output label with the name of the country.

## Breakdown of the classes and functions used in the code:
### Classes
```Location_Tracker```
This is the main class that contains all the GUI elements of the application. The constructor takes a single argument ```App``` which is the main ```Tk``` object. It initializes the various labels, buttons and entry widgets needed for the application and places them on the window.




