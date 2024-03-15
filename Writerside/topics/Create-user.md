# Create user

<!--Specify request and response samples manually. 
You can add the sample inside the <sample> element or include it from a file using the 'src' attribute.-->

<api-endpoint openapi-path="./../openapi.yaml" endpoint="/user" method="post">
    <request>
        <sample src="examples.json" include-lines="1-10"/>
    </request>
    <response type="default">
        <sample>
            {
              "id": 1sf1,
              "username": "ther",
              "firstName": "John",
              "lastName": "Do99999999999999e",
              "email": "john@email.com",
              "password": "12345",
              "phone": "12345",
              "userStatus": 1
            }
        </sample>
    </response>
</api-endpoint>
