There are 4 operations you can do
1. Get
2. Post
3. Put
4. Delete

The endpoints are as follows:
1. Get -> /services/apexrest/validify/restapi/v1/getData?id=<<ENTER ID HERE>>
2. Post -> /services/apexrest/validify/restapi/v1/PostData
Sample Body:

{
"referrals": [
{
"id": 867947,
"first_name": "Katrina2",
"last_name": "Jameson",
"referred_on": "2024-12-03T00:00:00Z",
"reffered_by": 48958 
}
]
}

3. PUT -> /services/apexrest/validify/restapi/v1/putData

{
"referrals": [
{
"id": 867947,
"first_name": "Katrina2",
"last_name": "Jameson",
"referred_on": "2024-12-03T00:00:00Z",
"reffered_by": 48958 
}
]
}
4. Delete -> /services/apexrest/validify/restapi/v1/deleteData?id=<<ENTER ID HERE>>


TO Test the above endpoints:

go to https://workbench.developerforce.com/restExplorer.php, login into the org

Use any of the endpoints and select the operation & click Execute.

For Post & PUT operations, you can paste the body in request body.
