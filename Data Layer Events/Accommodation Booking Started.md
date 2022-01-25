# Accommodation Booking Started

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Accommodation Booking Started",
    "booking": {
        "roomList": [
            {
                "room": {
                    "numAdults": <numAdults>,
                    "numberInMultiRoomReservation": <numberInMultiRoomReservation>,
                    "stayDate": "<stayDate>"
                }
            }
        ]
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|numAdults|integer|Integer number of adults for the booking.|1, 2, 3, 4, 5||||1|||
|numberInMultiRoomReservation|integer|Integer position of a room in a multi-room booking action.|1, 2, 3||||1|||
|stayDate|string|Date of each room night. ISO 8601 form \(YYYY-MM-DD\). Jan 1, 2019 is 2019-01-01|2001-12-22, 2011-01-01|^([0-9]{4})-(1[0-2]|0[1-9])-(3[01]|0[1-9]|[12][0-9])$||||||




