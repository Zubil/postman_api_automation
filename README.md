
# Writing a simple script to test a public API

1.Public API Reference - https://reqres.in/api/users?page=2 (*Mobiquity_Automated_API_Test.postman_collection.json*)

2.Public API Reference - https://gorest.co.in/public/v1/users (*Mobiquity_Automated_API_Test_2.postman_collection.json*)

3.Get the access token from https://gorest.co.in/consumer/login to update in this file - *Mobiquity_Automated_API_Test_2.postman_collection.json*

4.Update the Autohrization in Header with Bearer followed by your Access token

5.Below Authorization add Conten-type> application/json

**Note:** For the POST Request please update the user credential otherwise it will create an error due to already exiting user details

---

# We are using POSTMAN to test the API with basic testing scripts

1. **Mobiquity_Automated_API_Test.postman_collection.json** - This is a collection of tests with assertions to check the response of he website

2. **Mobiquity_Automated_API_Test_2.postman_collection.json** - This collection consists of creating a JSON request and to be sent to server and validating response
