# nosql-challenge

# 1. Download starter files

# 2. Import json as mongodb using this code within main folder:

#   mongoimport --type json -d uk_food -c establishments --drop --jsonArray Resources/establishments.json

# 3. In the NoSQL_setup_starter.ipynb file:

#       -check the new database and add the new restaurant
#       -update the BusinessTypeID for the new restaurant
#       -delete documents with LocalAuthorityName "Dover"
#       -update the data types for longitude and latitude across the collection

# 4. In the NoSQL_analysis_starter.ipynb file:

#       -find and count the establishments with a Hygiene score of 20
#       -find and count the establishments with a RatingValue of 4 or greater
#       -find the top 5 establishments with highest rating, sorted by lowest hygiene score, nearest to the new restaurant
#       -find and count the establishments that have a Hygiene score of 0