# Export Awagger documentation to Postman Collection

## What is Swagger?

Swagger is an amazing tool it Simplify API development, it helps you design and document your APIs while developing it and scaling it, thus saving time and having nice documention. it can be intgrated with many technology stacks.

## What is Postman?

Postman is an API platform for building and using APIs. Postman simplifies each step of the API lifecycle and streamlines collaboration so you can create better APIs—faster.

## How to export Swagger documentation to Postman Collection?

For Me Personally as for many devlopers i know like using Swagger for documentation but postman for testing.
thus this trick helps a lot:

1. Go To swagger documentation endpoint.
      
<img src="/main/api/Export%20Swagger%20documentation%20to%20Postman%20Collection/api-1.png" height="200" width="300"/>

2. Click on the link as highlighted below & Copy the URL. 
   
<img src="/main/api/Export%20Swagger%20documentation%20to%20Postman%20Collection/api-2.png" height="200" width="300"/>

3. Go To  Postman, Click Import at Top-Left corner:

<img src="/main/api/Export%20Swagger%20documentation%20to%20Postman%20Collection/api-3.png" height="200" width="300"/>

4. Switch to Link tab & paste the copied URL:

<img src="/main/api/Export%20Swagger%20documentation%20to%20Postman%20Collection/api-4.png" height="200" width="300"/>

5. Choose default settings & click Import:

<img src="/main/api/Export%20Swagger%20documentation%20to%20Postman%20Collection/api-5.png" height="200" width="300"/>

6. Your new collection will appear with all your endpoints and data:

<img src="/main/api/Export%20Swagger%20documentation%20to%20Postman%20Collection/api-6.png" height="200" width="300"/>


## Problem With Swagger & Postman?

The only problem with this approach, which developers been complining about for years know is there is no sync between both tool, each time you made changes to your API you will have to re-import  which leads to loose your testsm & data.

### You can follow this issue here:

https://community.postman.com/t/automatically-sync-openapi-swagger-spec-to-collection/8551

https://dev.to/iacons/synchronize-postman-collections-with-the-api-172i

https://stackoverflow.com/questions/68297972/how-to-update-postman-collection-from-swagger

https://stackoverflow.com/questions/68297972/how-to-update-postman-collection-from-swagger

https://goascribe.com/blog/using-swagger-documentation-postman-ascribe-apis/


##  Alernatives:

While trying to solve that problem i came acroos this promissing tools:

### APIDOG
