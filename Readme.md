Testing echo:

Method: Post 

URL   : https://general-service-dev.herokuapp.com/echo

Payload:
 
{
    "message": "Test Message"
}
Testing echoSecure:

Method: Post 

URL   : https://general-service-dev.herokuapp.com/echoSecure

Authentication : Basic Auth, username : testU, password: testP

Payload:
 
{
    "message": "Test Message"
}
Testing pureEcho:

Method: Put/Get/Post/Delete 

URL   : https://general-service-dev.herokuapp.com/pureEcho?myparam=123

Payload:
{
    "message": "Test Message"
}
HR Service : employees

Method: Get

URL : https://general-service-dev.herokuapp.com/hr/employees

Response : 
[
    {
        ExternalId: "E-001",
        Name: "Chintan Shah",
        DisplayUrl: "https://external.com/E-001",
        EmployeeAccountKey: "Account-001"
    },
    {
        ExternalId: "E-002",
        Name: "Chuck Summer",
        DisplayUrl: "https://external.com/E-002",
        EmployeeAccountKey: "Account-001"
    },
    {
        ExternalId: "E-003",
        Name: "Chris Walker",
        DisplayUrl: "https://external.com/E-003",
        EmployeeAccountKey: "Account-001"
    },
    {
        ExternalId: "E-004",
        Name: "Dan Topper",
        DisplayUrl: "https://external.com/E-004",
        EmployeeAccountKey: "Account-002"
    },
    {
        ExternalId: "E-005",
        Name: "Drew Berry",
        DisplayUrl: "https://external.com/E-005",
        EmployeeAccountKey: "Account-002"
    },
    {
        ExternalId: "E-006",
        Name: "Don Aiken",
        DisplayUrl: "https://external.com/E-006",
        EmployeeAccountKey: "Account-002"
    }
]    
HR Service : employees

Method: Get

URL : https://general-service-dev.herokuapp.com/hr/employee/Name/Chintan

Response : 
[
    {
        ExternalId: "E-001",
        Name: "Chintan Shah",
        DisplayUrl: "https://external.com/E-001",
        EmployeeAccountKey: "Account-001"
    }
]
