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

