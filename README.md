# Spreadsheets in Space ft. Racket

### Statement
XML API handling with Racket as well as data storage and visualization.

### Analysis

Data visualization will use recursion to parse information from storage and map/filter/reduce to highlight specific data points.(ex: Prices outside the normal range). Object-orientation can be used to pass groups of data for visualization in the UI.

### External Technologies
This project will be making calls to the eve-marketdata.com API which will return XML structs.

### Data Sets or other Source Materials
This project does not use other external Data sets.

### Deliverable and Demonstration
The deliverable will pull live data from the API, and display the data. It will also be able to display data from a period of time-though that data may be faked for demonstration purposes.

### Evaluation of Results
The program will display current prices given by the API, and update the storage files associated with our API call.

## Architecture Diagram
Upload the architecture diagram you made for your slide presentation to your repository, and include it in-line here.

API call will return XML struct which we then parse and save the data into the corresponding file for the type of data we made the call for. These files will then be parsed to display the data we want, which is determined by the user(day, week, month). Invalid typenames in the API will cause the program to reprompt the user for a typename. 

## Schedule 

### First Milestone (Sun Apr 9)
Mild anxiety and sparse thoughts on the subject of the final project. API call and XML parsing will be complete

### Second Milestone (Sun Apr 16)
Existential questioning of the validity of my education and data storage/call protocols will be established. 

### Public Presentation (Mon Apr 24, Wed Apr 26, or Fri Apr 28 [your date to be determined later])
Rachet UI will be finished.

## Group Responsibilities
1 man army over here.

**Additional instructions for teams of three:** 
stay hydrated.

### John Summers @Flannelz
