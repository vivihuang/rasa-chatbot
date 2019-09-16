## launch app

* LAUNCH
    - utter_launch

## find route

* ROUTE{"startLoc_city":"西安","endLoc_city":"北京"}
    - slot{"endLoc_city":"北京"}
    - slot{"startLoc_city":"西安"}
    - utter_query_route

## find recipe

* QUERY{"dishName":"酸辣粉"}
    - slot{"dishName":"酸辣粉"}
    - utter_query_recipe
