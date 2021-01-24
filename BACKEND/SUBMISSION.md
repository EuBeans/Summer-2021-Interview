## Repository: 

```
https://github.com/EuBeans/RestAPI-Problem.git
```

## Run Instructions

This app uses node js and postgres. Most of the endpoints are POST request, this means that you will need to run curl commands in the command promp to call those endpoints. There is a "testingAPI.txt" in the testing folder which contains curls command line example to test most of the POST endpoints.

To run this application you will need to open the directory of the project in command prompt and run "node index.js"
To test the GET request simply open your browser and search the following URL:  http://localhost:3000/[endpoint]/{OptionalParam}/

Here are the possible endpoints: 

app.get('/listOfRecipe/:id', db.getListOfRecipes)
app.get('/listOfRecipe/', db.getListOfRecipes)
app.post('/update/:id', db.updateRecipe)
app.post('/create/:id', db.createNewRecipe)
app.post('/UpdateToPremium/:id', db.UpdateToPremium)
app.post('/UpdateToNonPremium/:id', db.UpdateToNonPremium)
app.post('/delete/:id', db.deleteRecipe)
app.post('/getRecipe/:id', db.getRecipe)


## Additional Information
student number: 300061464
full name : Jean pierre Sfeir

Wasn't to sure how to share the postgresql database through github, was trying to figure a way to share a static version of the database but after some research I realized that GitHub only supports static database such as Firebase.
