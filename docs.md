### API Documentation

[postman documenataion](https://documenter.getpostman.com/view/6882292/SzmfXwnW)

##### How to get API_KEY

* Send ```/start``` to [@covid_api_bot](https://t.me/covid_api_bot) on telegram


##### Methods

1. ```GET``` ```/get```

    **URL Params**
    * token (string - required)
    
    **Data Params**
    * query (json - optional)
    
    eg) ```/get?token=API_TOKEN&query={"sort":"total_cases"}```
    
2.  ```GET``` ```/continent```

    **URL Params**
    * token (string - required)
    * continent (string - required)
    
    **Data Params**
    * query (json - optional)
    
    eg) ```/continent?token=API_TOKEN&continent=Europe```
    
3.  ```GET``` ```/country```

    **URL Params**
    * token (string - required)
    * country (string - required)
    
    **Data Params**
    * query (json - optional)
    
    eg) ```/country?token=API_TOKEN&country=USA```

##### Query Parameters

1. date     - date you want to query in unix timestamp
2. sort     - sort based on the sort query string
3. continent- set false to hide continent details
4. test     - set false to hide total tests done
5. sort_asc - set true to show results in ascending order
5. next     - key to paginate through results
