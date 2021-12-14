
- Custom Connectors
- Don't pile up actions/operations.
- Keep it less than 100
- Breakit if need in to separate connectors
- Triggers 
=====================

Power Automate :
= Build Connectors

===========Environments================
Microsoft maintains data based on Environments

Default
Dev
Prod
Strategik Prev : Preview Environment

Custom Connector :
[
    US Region
    EMEA
    ASIA
    INDIA
]


Technical Level

1 : NO CODE
2 : SOME Code : Azure Portal : Logic Apps
3 : High Level Coder
- Azure Functions

Flow vs Azure Logic Apps

Custom Connectors
=> Flow, Logic App, Power Apps

?querystring based on 

getStudentData

if(the student came have arrears) ?include_arrears=true

policy :
{

setQueryString
setheaders

}


Core : apiSwagger.definition.json
Custom Properties : apiProperties.json
Branding : icon.png
Identity : settings.json

script.csx : Leveraged this feature for a great user experience of
custom connector

C# Code

HTTP interceptors : 

folder_formatted:["f1","f2"],
folders:[
    {
        name:"f1"
    },
    {
        name:"f2"
    }

]

title:"Client Secret",
x-ms-summary : "Client API Password"
x-ms-dyanmicValues :{
    data : GetStudents
}
x-ms-dynamicProperties :

context.Request.QueryStrings.Add("include_arrears",true)

{

"student_details":{"score":34,grade:12,"arrears":[]}

}
context.Response=JSONSerializer.parse({"score":34,githubid:"studenaa",grade:12,"arrears":[]});



Compose :

commit_count=makeHttpRequest("http://github.com/studenaa/commit");

response["commit_count"]=commit_count
response["student_details"]?["score"]
response["score"]


DocuSign : 




Solution Based
or use paconn : power automate custom connector cli

https://api.freeagent.com/v2/contacts


REST API

/contacts

METHOD : GET
/contacts/{contact_id}

METHOD : DELETE
/contacts/{contact_id}

POST : New Record
PUT : UPDATE Record
PATCH : Partial Update








