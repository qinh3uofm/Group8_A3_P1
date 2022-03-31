# Music Events in Manitoba

This API provides information about upcoming music-related events in Manitoba. Results given will be based on a provided latitude and longitude or date.

The API response will contain the name of music events in Manitoba, their respective venues and dates, admission costs, and website. More information about the response can be found in the [sample response](https://github.com/qinh3uofm/Group8_A3_P1/) section.

# Endpoints

There is one endpoint for our API. Use a GET a request to get a response from the API. 

GET /events → Lists all music events that will happen in Manitoba

Parameters

Parameter         Type         Required        Description

lat            float        Yes            The latitude of the event
lon            float         yes            The longitude of the event
date            String        yes            The date of the event

