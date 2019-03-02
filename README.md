# ReadCSVfileSQLFilterthenWriteCSVfile-

Project Blog Article Here: https://portfolio.katiegirl.net/2019/03/02/using-perl-to-execute-sql-on-data/

Simple PERL script to import a CSV file (contains records of data - could be a dump from a database), execute custom SQL, and write back to a CSV file.

  ReadCSVfileSQLFilterthenWriteCSVfile 
  File: ReadCSVfileSQLFilterthenWriteCSVfile.pl
 

  This script uses an example of SQL to filter out select records
  
  DBI is used in this example
 
  Input files: (same directory)
  
  input.csv located in same directory as script
 
  Output files: (same directory)
  
  output.csv
 
  CASE Example
 
  input.csv 
 
  RECORD,FOOD,COUNTRY,REGION,COLOR,SEQUENCE
  
  422,TACO,FRANCE,SOUTH,RED,A
  
  423,CHEESEBURGER,FRANCE,SOUTH,BLUE,B
  
  424,BURRITO,FRANCE,SOUTH,GREEN,C
  
  425,CAKE,FRANCE,SOUTH,YELLOW,D
  
  426,CUPCAKE,FRANCE,SOUTH,PURPLE,E
  
  427,STEAK,FRANCE,SOUTH,ORANGE,F
  
  428,HAM,FRANCE,SOUTH,BLACK,A
  
  429,EGGS,FRANCE,SOUTH,WHITE,B
  
  ...
  
  output.csv (filter COLOR=GREEN, COUNTRY = FRANCE)
  
  RECORD,FOOD,COUNTRY,REGION,COLOR,SEQUENCE
  
  424,BURRITO,FRANCE,SOUTH,GREEN,C
  
  436,CHICKEN,FRANCE,SOUTH,GREEN,C
  
  448,EGGS,FRANCE,SOUTH,GREEN,C
  
  460,TACO,FRANCE,SOUTH,GREEN,C
  
  ...
 
 
  About 		  
 
  Author: Kathleen West 
  SUPPORT WOMEN IN TECH 
  https://www.linkedin.com/in/kathleenewest
 
  FAQ's
 
  Why Did You Make This?
 
  I made this project to demonstrate my PERL coding skills and that YES, when I say
  I have 15+ years work experience in industry, I really do know how to make a 
  project work. I have made many more PERL scripts for my employers and consulting
  clients to download data from databases, manipulate, report, and or transmit to
  other databases, the Internet, and computer modeling applications. I achieved this
  project working independently as the sole developer and IT solutions engineer.
  
  I See Code Improvments and Ideas, Can I Contribute?
 
  Yes, there are a plenty ways to make this script better. I do not have time
  or interest to discuss and address every comment. I do not plan to
  make frequent, if any, updates to this project. You may make your own code
  project sites and grow the knowledge community. 
 
  License, Terms of Use?
 
  You may use, modify, or learn from this script to help you with your next PERL project 
  either for school or company projects. 
  Be fruitful with your PERL, prosper, and contribute to the knowledge community.

