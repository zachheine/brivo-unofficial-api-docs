2004: Open
```
"securityAction":{  
  "securityActionId":2004,
  "action":"Open",
  "securityActionType":{  
    "typeKey":"security_event_type.successful_access",
    "description":"Access attempts that do result in granted access"
  },
  "exception":false,
  "priority":"LOW"
},
```

5006: Invalid Cred Threshold Passed
```
"securityAction":{
  "securityActionId":5006,
  "action":"Invalid Cred Threshold Passed",
  "securityActionType":{
    "typeKey":"security_event_type.failed_access",
    "description":"Access attempts that did not grant access"
  },
  "exception":true,
  "priority":"MEDIUM"
}
```

5012: Failed Access Unknown Cred
```
"securityAction":{
  "securityActionId":5012,
  "action":"Failed Access Unknown Cred",
  "securityActionType":{
    "typeKey":"security_event_type.failed_access",
    "description":"Access attempts that did not grant access"
  },
  "exception":true,
  "priority":"MEDIUM"
}
```

5017: Failed Access User Not Enabled
```
"securityAction":{
  "securityActionId":5017,
  "action":"Failed Access User Not Enabled",
  "securityActionType":{
    "typeKey":"security_event_type.failed_access",
    "description":"Access attempts that did not grant access"
  },
  "exception":true,
  "priority":"HIGH"
}
```

5034: Undownloaded Credential
```
"securityAction":{
  "securityActionId":5034,
  "action":"Undownloaded Credential",
  "securityActionType":{
    "typeKey":"security_event_type.failed_access",
    "description":"Access attempts that did not grant access"
  },
  "exception":false,
  "priority":"LOW"}
```
