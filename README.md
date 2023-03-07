# nosql-challenge
This week's NoSQL Challenge is divided into 3 Parts:

    Part 1: Database and Jupyter Notebook Set Up
        - deliverable can be found in "NoSQL_setup_starter.ipynb"
        - method used for importing the data from Terminal is included in the markdown cell in the notebook
    
    Part 2: Update the Database
        - deliverable can be found in "NoSQL_setup_starter.ipynb"

    Part 3: Exploratory Analysis
        - deliverable can be found in "NoSQL_analysis_starter.ipynb"
        - exact latitude and longitude for "Penang Flavours" were taken from pprint(establishments.find_one({"BusinessName":"Penang Flavours"})) results:
            {'AddressLine1': 'Penang Flavours',
            'AddressLine2': '146A Plumstead Rd',
            'AddressLine3': 'London',
            'AddressLine4': '',
            'BusinessName': 'Penang Flavours',
            'BusinessType': 'Restaurant/Cafe/Canteen',
            'BusinessTypeID': 1,
            'Distance': 4623.972328074718,
            'LocalAuthorityCode': '511',
            'LocalAuthorityEmailAddress': 'health@royalgreenwich.gov.uk',
            'LocalAuthorityName': 'Greenwich',
            'LocalAuthorityWebSite': 'http://www.royalgreenwich.gov.uk',
            'NewRatingPending': True,
            'Phone': '',
            'PostCode': 'SE18 7DY',
            'RightToReply': '',
            'SchemeType': 'FHRS',
            '_id': ObjectId('6406a20e55dad77fdd77e0fb'),
            'geocode': {'latitude': '51.49014200', 'longitude': '0.08384000'},
            'scores': {'ConfidenceInManagement': '', 'Hygiene': '', 'Structural': ''}}