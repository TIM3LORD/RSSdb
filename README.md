# RSSdb
RSS feed to firebase real time db



v1 --> firebasetest -->Stores data from hardcoded RSS links to realtime db

   -->RSS basic test --> basic RSS reader with hardcoded links
   


v2 --> Pulls list of links from db

   --> RSS link fetched from db dynamically
   
   -->Added list of continious numbers to identify each entry to database (Redundancy Problem)
   


v3 --> Added Support for Reddit Links

   -->Added Parsing Reddit dateTime string
   
   -->Eliminated Redundancy Problem by setting datetime string as unique identifier for each post instead of a list of numbers
   
   -->Added Description to each feed data
   
   -->Reddit Description problem solved by setting description to no description found
   
   
   
   
   RSS_Firebase_Frontend
   
   v1 --> Basic pull from database
   
   
   v2 --> refresh on new data
      --> Changed id to class for '<p>' elements
