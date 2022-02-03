[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/457511ff990af3e590d4?action=collection%2Fimport#?env%5BProdEnvironment%5D=W3sia2V5IjoiaG9zdCIsInZhbHVlIjoiaHR0cHM6Ly9yZXFyZXMuaW4iLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6Imh0dHBzOi8vcmVxcmVzLmluIiwic2Vzc2lvbkluZGV4IjowfV0=)



Commandline
-----------------------
Newman is a command-line collection runner for Postman

Step 1 : check if node.js is already installed
             node -v
  node --version
             npm -v

Step 2 : Install node.js
             https://nodejs.org/en/download/
             Check if node and npm are installed

For Mac using brew
https://www.dyclassroom.com/howto-mac...

Step 3 : Install Newman
             npm install -g newman

Step 4 : Export collection as json file

Step 5 : On cmd goto location of collection json file

Step 6 : Run command
 newman run collectionfilename.json

Data Driven testing
How to refer data from CSV and JSON files
Demo in the video
1. How to get data from CSV file
2. How to get data from JSON file
3. How to Run data-driven API Requests
4. How to Run data-driven Tests
5. How to run data-driven tests from the command line

You can use data variables in all places and in the exact way you can use environment variables, except in pre-request and test scripts.# postman-ddt
