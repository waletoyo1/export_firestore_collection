# export_firestore_collection

https://gunargessner.com/firestore-backup


ALGOLIA/FIRESTORE IMPORT
#Install npx globally:
npm install --global npx.

# Add GOOGLE_APPLICATION_CREDENTIALS to environment variable and its path will be the path to the service key json file. Then restart your computer
#Run each of this line, starting with "set" for windows and "export" for Mac,  and press enter:

LOCATION=us-central1
  PROJECT_ID=rxlink-app
  ALGOLIA_APP_ID=-------
  ALGOLIA_API_KEY={ unspecified parameter }
  ALGOLIA_INDEX_NAME=firestore_collection_name
  COLLECTION_PATH=firestore_collection_name
  FIELDS=name,uid,picUrl..etc
  TRANSFORM_FUNCTION={ unspecified parameter }
  GOOGLE_APPLICATION_CREDENTIALS=</path/to/service/account/key>
  E.g set LOCATION=us-central1, then press enter
  
  #Finally, paste npx firestore-algolia-search and follow the command instructions to complete the import
