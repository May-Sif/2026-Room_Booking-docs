# Entity Relationship Diagram

## Entities

### User
- Id
- Name
- Email
- Role

### Room
- Id
- RoomCode
- Name
- Capacity
- Building
- Floor
- Status

### Booking
- Id
- UserId
- RoomId
- StartTime
- EndTime
- Status

## Relationships

User (1) —— (N) Booking
Room (1) —— (N) Booking
