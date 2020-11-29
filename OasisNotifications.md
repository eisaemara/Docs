# Oasis Notifications .
This document describe how to send SMS,EMAIL,APP_NOT using Oasis notification table 

## SMS 
| Column Name |  Description  |
|---|---|
| notification_id  | notification_id.next_val  |
| notification_type  | SMS  |
| context_type  | PATIENT_ID,STAFF_ID  |
| context_id  |  patient_id,staff_id |
| status  |  `P` |
| payload  | json object in the following format  `{"mobileNo":"<mobile_no>" , "message":"<message to send>" }`  |

## E-MAIL 
| Column Name |  Description  |
|---|---|
| notification_id  | notification_id.next_val  |
| notification_type  | MAIL  |
| context_type  | PATIENT_ID,STAFF_ID  |
| context_id  |  patient_id,staff_id |
| status  |  `P` |
| payload  | json object in the following format  `{"to":"<email-addresses>" , "subject:<email-subject>" , "body":"<email-body>" , "attachement":[<base64-attachement>] , "attachement-name":[<attachement-name>] }`  |

## APPNOT 
| Column Name |  Description  |
|---|---|
| notification_id  | notification_id.next_val  |
| notification_type  | MAIL  |
| context_type  | PATIENT_ID,STAFF_ID  |
| context_id  |  patient_id,staff_id |
| status  |  `P` |
| payload  | json object in the following format  `{"to":"<email-addresses>" , "subject:<email-subject>" , "body":"<email-body>" , "attachement":[<base64-attachement>] , "attachement-name":[<attachement-name>] }`  |