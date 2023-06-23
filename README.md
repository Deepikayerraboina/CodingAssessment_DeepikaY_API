# CodingAssessment_DeepikaY_API

I haves selected option -Creating tests for GET API and validate the Response

Added dependecy- 
1.RestAssured Api's
2.testNg
3.Maven build Tool


Created tests methods --
1.ValidateResponseCode_GetAPI
2.validateFestivalNameValuesNotnull
3.validateBandDataNotNull

Details test Method 1
-- Performing the Get Call to API
--Validating the response code

Details test method 2
-- getting the reponse from Test method 1
-- validate the Music Names in sorted order
-- validating the name Value is not null

Details test method 3
-- getting the reponse from Test method 1
-- validate the Music Band dats Names and record label in sorted order
-- validating the Band data Values are not null

--Created APITests Package
- Created Class GetApitests

- Executing from testng.xml

- As on hitting the on Get call
- the HTTP Response always varies

  --Validating the Response codes and validating the  response received have response body for get APi
     based on above i am testing the next test methods.
  --Put check point for the data recevided for Music Name - sorted Order
  --put checkpoint for the dat received for Festiaval band- not contain null values
  

