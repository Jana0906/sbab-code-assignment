# sbab-code-assignment
Challenge- description
The task is to write an application to find out which bus lines have the most bus stops on
their route and list the top 10 as clear text. The application should also list the names of every
bus stop of the bus line that has the most stops. There is no requirement on how the bus
stops are sorted.
To accomplish the task please use the Trafiklab’s open API (https://www.trafiklab.se). You
can find more information about the specific API on the documentation page:
http://www.trafiklab.se/api/sl-hallplatser-och-linjer-2

# Steps to run the application on Windows:

Clone the Repository:
Open Command Prompt or Git Bash and run:
git clone https://github.com/Jana0906/sbab-code-assignment.git

Navigate to the Project Directory:
cd sbab-code-assignment

Build the Project:
mvn clean install

# The code is written in Java.
(http://localhost:8080/lines) will return the top 10 lines with the most bus stop stations
(http://localhost:8080/lines?top=3) with top RequestParam you can choose the number of bus lines with the most stop stations tex.3

