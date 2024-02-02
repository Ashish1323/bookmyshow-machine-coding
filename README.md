# Class Diagram: BookMyShow

## BookMyShow Class
- **Attributes:**
  - users: Map
  - events: Map

- **Methods:**
  - +addUser(userId, userName, userMail)
  - +addEvent(eventId, eventType, eventName, eventCity, eventNoOfBookings)
  - +addBooking(userId, eventId, noOfBookings)

## User Class
- **Attributes:**
  - userId
  - userName
  - userMail
  - bookingCount

## Event Class
- **Attributes:**
  - eventId
  - eventType
  - eventName
  - eventCity
  - eventNoOfBookings
