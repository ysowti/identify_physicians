# Doximity's Data Scientist Assignment
##### Proprietary and Confidential
------------


You are working for a large marketing firm that targets doctors based on their practice area. Your current campaign is targeting Cardiologists, and you are tasked with coming up with a list of doctors to contact.

You are given a file, **`physicians.csv`**, which contains a list of doctors and their unique specialty. You notice that there are a decent number of doctors with "Cardiology" as a specialty, but there are also quite a few doctors whose specialty is "Unknown". You wonder if any of these doctors might actually be Cardiologists.

You find a public dataset, **`procedures.csv`**, which contains a list of procedures your doctors performed over the past year.
The columns of this dataset are as follows:

* **`physician_id`** unique physician identifier, joins to `id` in **`physicians.csv`**
* **`procedure_code`** unique code representing a procedure
* **`procedure`** description of the procedure performed
* **`number_of_patients`** the number of patients the doctor performed that procedure on over the past year

------------

Using this procedure data, determine whether the pool of Cardiologists can be increased.

Both files can be found in this repository. Please submit all relevant code and write a detailed explanation of your methodology and results. Assume both a data scientist and a product manager will look over your results. We’re a Python shop - feel free to use any libraries you see fit.

------------

## Instructions for Submission via Github

* Create a Github FORK of this repository on your own Github account. 
* Next create a git branch with your changes, and push a pull-request to your fork. [(Help)](https://www.dropbox.com/s/xxqxdlmmc26hl0q/Screen%20Shot%202017-06-02%20at%2015.28.36.png?dl=0)
* Add @doximity-review as a collaborator to your fork. 
* Email your point of contact at Doximity a link to your repository to let them know you are done with the assignment. 
