## What Actors should be in the Diagram?
- Actors;
  - Students
      - All Students can fall under one actor role, the one possible ones who would require a separate actor role would be those who require or consistently book specialised equipment.
  - Faculty;
      - Lecturers may be the ones who possibly; assign, grant permission or give reason for booking equipment/specialised equipment.
      - It Technicians will need to be included due to technological equipment (i.e. laptops) malfunctioning or requiring service.
      - Equipment Technicians is a potential role if it is not already existing. This system will require a management to overlook it, the technicians could be a mix of IT and library staff.
          - Furthermore; equipment Technicians would be responsible for the acceptance of returned equipment and managing equipment availability to avoid hogging, theft or a low stock of equipment come project/exam                      deadlines.
      - Management and Finance Management; These two roles may not be 2 individual people, nor must it be multiple people, it would depend on the college and how they choose to run things.
          - This roles would be responsible for ordering more or ordering replacement equipment. It would be a technicians job to notify them of the shortage or theft and these roles would follow up and fix the reported                 problems.

## What are the confirmed use cases?
- Booking Equipment
- Returning Equipment
- Reporting Equipment as;
  - Damaged.
  - in need of service.
  - Needing permission granted to accomplish task or project.
  - Stolen.
- Ordering More equipment.
- Possibly Authorising the booking of specialised equipment. (Likley less of them and more expensive, so they may need a tighter leash before being loaned to students who actually need them.)
- Fixing Equipment;
  - Updates.
  - Replacing damaged or missing pieces.
  - Cleainging.



# Activity Diagram
### Draw.io; Used for Diagram creation, current applicable diagram ver: 2.9

## Process Modelled
???

## Purpose
The diagrams purpose is to visualise the process in which the system will operate.
Currently the diagram shows that the system will allow a student to;

Check Equipment Availability for X Date --> IF TRUE --> Book Equipment for X Amount of Time --> X Time Later --> Return Equipment --> IF ISSUE WITH EQUIPMENT --> Report Problem to Equipment/IT Technician(s).

Check Equipment Availability for X Date --> IF FALSE --> Cannot Book Equipment for this Date --> RESTART

Check Equipment Availability for X Date --> IF TRUE --> Book Equipment for X Amount of Time --> X Time Later --> Return Equipment --> IF NO ISSUE --> RESTART

This is the longest path within the diagram and shows off the most of it. I expect to add and improve it further as time progresses.

## Activities
- Checking Availability.
- Booking Equipment.
- Return Equipment.
- Reporting Issue with Equipment.
- Fixing Issue(s) with Equipment.
- Ordering more/Replacing Equipment.

### Possible more Activities/Use Cases;
- Authorising Booking of Special Equipment.
- Pursuing Legal Action for Misuse and/or Theft of Equipment.
- Request Extension on Current Booking.
- Authorise Booking. (i.e. Student may require reason from lecturer(s)/modules in order to apply for equipment.)

## Decision & Guards


## Unknowns


## Stakeholder Questions


## Modelling Decision


## Reflection


