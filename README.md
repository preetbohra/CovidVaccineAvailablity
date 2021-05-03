# CovidVaccineAvailablity
Sends an email to the user if Covid Vaccine is available in his/her City

This is a very simple executable. First you run the InitialChecks.exe which would ask you for your city name. Then it traverses through all the states to validate your city and creates a text file called districtId since the Setu API Requires District ID.
After the District ID is fetched, you would have to provide your email address or set of email addresses who need to be notified of the availablity of the vaccine.

When this inital setup is complete you can directly run the "Final Script.exe" or schedule it ( *using Task Schedular for Windows* )

This is just a project I developed for the responsible members of the Indian Society.

Please do use it and let me know if there are any shortcomings.
