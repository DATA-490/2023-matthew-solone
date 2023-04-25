# <Project Title>
* **Author**: Matthew Solone, github: [mjsolone]([<url link to github profile>](https://github.com/mjsolone))
* **Major**: Mathematics / Statistics
* **Year**: Senior

# Type of project

An automation and streamlined data intake system for the Center for Regenerative Agriculture and Resilient Systems (CRARS).

# Purpose (including intended audience)

The Center for Regenerative Agriculture and Resilient Systems (CRARS) mission is to investigate, develop, demonstrate, and educate about comprehensive, regenerative practices that both restore and enhance the resiliency of living systems and communities. CRARS takes on clients from around the state to provide analyses of soil and food samples, allowing clients to improve upon their regenerative practices.
    
This project aims to streamline the soil sample intake process for the Center of Regenerative Agriculture and Resilient Systems (CRARS) using barcode scanners. The CRARS team currently uses Slack communication in addition to a collaborative Excel document to update other team members on their progress in the lab, which can lead to lost or overlooked updates on sample progress through the intake process. By implementing a tracking system using barcodes, the team will be able to clearly document each stage of sample intake and testing, including receiving, sieving & grinding, vialing, and the pre-transport check.


# Explanation of files

* `CRARS490.qmd` - This is the file that will generate the HTML report for the CRARS admin. Contains the R script to load, manipulate and display the data from the google sheet.

* `Barcode_Scanner_Responses_-_Input_1.csv` - This is a CSV file of Mock Data genraged from the google form connected to the Google Form. You can find the Google Sheetg here: https://docs.google.com/spreadsheets/d/1PCCSZJhs9f4raQyxGGcWhFUCayHHUjMhjVCcoVDrWaI/edit#gid=718808986
    - Variables: 
        - Timestamp - The date/time of when a Sample was entered into the form (ex. 3/23/2023 1:25:50)
        - Barcode - The barcode of the sample that was entered. (ex. 12-890)
        - Employee - The first and last name of the employee that is handling the sample (ex. Matt Solone)
        - Sample Status - The status of the sample through the intake process (ex. Recieved, Sieved & Grinded, Vialed, "Pre- transport Check")
        - In-out - Whether the sample is being entered or pulled uut of a process.
        
* `Google Form` - This is the link to the Google Form which CRARS will use for intake of soil samples : https://docs.google.com/forms/d/e/1FAIpQLSemyy0nJerkPJuGTeoowvoiGapRjRUDSFADBxfyBilZgUfiSw/viewform?usp=sharing

# Completion status 

<as applicable> Pending steps include: 

- [ ] <thing 1>
- [ ] <thing 2>

## Enhancements: 
<List at least 2>

- [ ] Consider using GitHub Pages to produce a website for CRARS
- [ ] Reformat the QMD to produce a more visually appealing report 
- [ ] Consider looking into more time series graphs for sample tracking

# Can someone else work on this project? 
Yes!

# Public Display/dissemination

* Project was presented at the Spring 2023 Chico State College of Natural Sciences poster session. 

# License
