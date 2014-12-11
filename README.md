MongoDB
Overview

In this assignment, you will need to download a complete file of zipcodes and population statistics from the US 2010 census and then post it to your i6.cims.nyu.edu account. The file is available here as zips.json.

(Source: These data can be found in .csv format on the 2010 US Census Data site; and in .json format on the MongoDB tutorials site. Please use .json data for this assignment.)

Steps

Obtain and upload the .json zip codes & population count statistics file to your i6 account. Make sure the permissions are set to "644" - that is, that the file is world-readable but nobody else can edit it.
Start up mongo per the instructions we have reviewed in class for using mongodb on i6.
Import the data into your mongo database using mongoimport.
Then answer the following questions by writing queries and displaying the results. Note 12/10/2014: The zip codes are in the "_id" field.

General Queries:

How many zip codes are there in your home state?
List the five least populated zipcodes (those that have the smallest populations) in Texas. (Hint: Be sure to exclude zip codes with a population of zero; as these data are possibly missing or incorrect.)
List the zip code and population for three zip codes in Brooklyn.
How many zip codes are there altogether in the Continental United States (excluding Hawaii, Alaska and Puerto Rico)?
How many zip codes are there altogether in New York, New Jersey, and Pennsylvania (NY, NJ, PA)?
Write two additional analytic queries of your choice for any state or group of states.