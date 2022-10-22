I dusted this off after 11 months. I was able to get it to run in the cerner sandbox at https://code-console.cerner.com/console/edit/f72c1fc4-e0d5-4c7f-a71c-d30cd5cddbad/b9085b64-3b43-4a72-877d-f2deeff4b988 and also to modify the code so that the actual resource json of a patient and that patients observation will show on the console. I save them in this project as patient.json and observations.json .

That was with the Cerner sandbox set at DSTU2. When I bumped it up to R4 the sandbox responded with "Failed to call FHIR service". I noticed that the fhir-client is ancient so I downloaded v2.0.7. 

My goal is to set up a patient facing app that allows me to download those resource on Cerner, Epic and Elation. Then I have much of my post 2015 chart in one file. 

Now have changed to simple index and laund files and set aside the originals as index-original.html and launch-original.html. 