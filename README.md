# api endpoints and operations
/api/near-miss
- <span style="color:green">**GET**</span>
```
{
      "id": "1", 
      "type": "Action",
      "natureOfAction": "Rubber seal was temporary repaired",
      "dueDate": "08/21/2018",
      "responsibility": "Cheif officer",
      "status": "/",
      "dateCompleted": "08/21/2018"
}
```

/api/incident
- <span style="color:green">**GET**</span>
```
{
      "id": "07-2020",
      "securityLevel": "Major",
      "type": "Injury",
      "vessel": "Vessel 4",
      "date": "12 jan 2020",
      "taskInvolved": "Cargo Operation - Loading",
      "description": "During the loading of a Toxic Cargo it was seen that the duty AB was not wearing suitable PPE",
      "impactOn": "Personal",
      "status": "Closed"
}
```

/api/notification
- <span style="color:green">**GET**</span>
```
{
    "id": "01887262222",
    "title": "Injury During Lifeboat Launching",
    "lesson": "Lifeboat hooks if not properly set after a drill or actual use can lead to an incident. All vessels should ensurethat after securing up of lifeboats the hooks are checked",
    "lessonType": "Procedure",
    "deficiencyGroup": "5 - Safety",
    "targetGroup": "All Crew"
}
```
