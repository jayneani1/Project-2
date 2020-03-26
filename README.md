# Project-2

# Project Overview

## Project Links

- [add your github repo link]()
- [add your deployment link]()

## Project Description

I was also thinking of recreating the site called the Doe Network or creating a site that lets you input attributes and discover missing people/ Jane and Jon Does who have those. Most of the sites I see have horrible sites and could be easier to navigate. I couldn't find an api for those because most of them are private. I found one that I'm not sure is useable.

If the missing person API is not great, I would like to recreate the Petfinder app. 

## API

https://www.petfinder.com/developers/v2/docs/

https://public.opendatasoft.com/api/records/1.0/search/?dataset=namus-missings&facet=cityoflastcontact&facet=countydisplaynameoflastcontact&facet=raceethnicity&facet=statedisplaynameoflastcontact&facet=gender


```
},
"records": [
{
"datasetid": "namus-missings",
"recordid": "a22eddc200a806791c57a1ae45b0baeafeca7e44",
"fields": {
"currentagefrom": 59,
"cityoflastcontact": "Escondido",
"firstname": "Michael",
"modifieddatetime": "2018-05-09T17:52:08+00:00",
"middlename": "William",
"gender": "Male",
"image": {
"mimetype": "image/png",
"format": "PNG",
"color_summary": [],
"filename": "Thumbnail.png",
"width": 120,
"id": "a909472d1b66b57973f56648a8c520a0",
"height": 120,
"thumbnail": true
},
"currentageto": 59,
"geo_point_2d": [
33.1192116121,
-117.086432917
],
"computedmissingminage": 50,
"countydisplaynameoflastcontact": "San Diego",
"computedmissingmaxage": 50,
"idformatted": "MP34938",
"raceethnicity": "White / Caucasian",
"link": "https://www.namus.gov//MissingPersons/Case#/34938",
"statedisplaynameoflastcontact": "CA",
"lastname": "Sholes",
"geo_shape": {
"type": "Point",
"coordinates": [
-117.0864329172,
33.1192116121
]
},
"dateoflastcontact": "2009-11-10",
"namus2number": "34938"
},
"geometry": {
"type": "Point",
"coordinates": [
-117.086432917,
33.1192116121
]
},
"record_timestamp": "2018-05-29T01:14:51.907000+00:00"
},
```


## Wireframes

Upload images of wireframe to cloudinary and add the link here with a description of the specific wireframe. Also, define the the React components and the architectural design of your app.

- [add link to your wireframes]()
- [add link to your react architecture]()


### MVP/PostMVP - 5min

The functionality will then be divided into two separate lists: MPV and PostMVP.  Carefully decided what is placed into your MVP as the client will expect this functionality to be implemented upon project completion.  

#### MVP EXAMPLE
- Find and use external api 
- Render data on page 
- Allow user to interact with the page

#### PostMVP EXAMPLE

- Add localStorage or firebase for storage

## Components
##### Writing out your components and its descriptions isn't a required part of the proposal but can be helpful.

Based on the initial logic defined in the previous sections try and breakdown the logic further into stateless/stateful components. 

| Component | Description | 
| --- | :---: |  
| App | This will make the initial data pull and include React Router| 
| Header | This will render the header include the nav | 
| Footer | This will render the header include the nav | 


Time frames are also key in the development cycle.  You have limited time to code all phases of the game.  Your estimates can then be used to evalute game possibilities based on time needed and the actual time you have before game must be submitted. It's always best to pad the time by a few hours so that you account for the unknown so add and additional hour or two to each component to play it safe. Also, put a gif at the top of your Readme before you pitch, and you'll get a panda prize.

| Component | Priority | Estimated Time | Time Invetsted | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Adding Form | H | 3hrs| 3.5hrs | 3.5hrs |
| Working with API | H | 3hrs| 2.5hrs | 2.5hrs |
| Total | H | 6hrs| 5hrs | 5hrs |

## Additional Libraries
 Use this section to list all supporting libraries and thier role in the project such as Axios, ReactStrap, D3, etc. 

## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of an a brief description.  Code snippet should not be greater than 10 lines of code. 

```
function reverse(string) {
	// here is the code to reverse a string of text
}
```
