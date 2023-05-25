# us-county-codes-json
Made this for the Wikicommons US Map with all the counties.

I couldn't find this data readily available, except in a pdf file, the pdf file used to generate the JSON is included

You can play around with the data with this API:

http://epitheus.com/county_api/v1/

![us_counties](https://github.com/tordener/us-county-codes-json/assets/5913474/42996e21-076f-48f8-9072-4654ab69595f)

## Object format:
```json
{
    "state":"ALABAMA",
    "stateCode":"01",
    "cityCode":"00124",
    "cityName":"ABBEVILLE",
    "countyCode":"067",
    "countyName":"HENRY"
}
```

## The full county code, if you'd like to address the county in the SVG, is the stateCode + countyCode</h3>
