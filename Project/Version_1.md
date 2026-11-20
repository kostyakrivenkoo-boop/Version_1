Information here is a basic draft with what came to mind on a certain topic not all of it will be used in a final project 

## Scenario A - Community Volunteer & Event Coordination System

## Facts:
 - It takes a lot of time to match volunteers to activities
 - Sometimes it's not clear which activity needs help
 - Some activities required certain experience or skills 
 - Volunteer information stored in different places
 - Organisers don't know who is attending activity
 - Organisers not usually know who is available
 - Signing up for event is mixed and can be done by phone calls, spread sheets and paper form
 - Accessibility and privacy need to be considered
 - Events are local

## Assumtions:
 - Only certain amount of people can sign up for the event
 - Registration for event closes certain time before event 
 - It might be an age restriction for certain events
 - Event might be closed any time
 - Certain information about event can see only andmis 
 - Registered volunteer might want to withdraw registration 
 
## Unkowns
| Question | Who can answer |
| -------- | -------------- |
| How many volunteers can be on an event? | Event holder |
| Can volunteer apply for different events at the same time? | IT Specialist |
| What information should volunteers provide? | Event holder |
| Are particular skills or qualifications required for some activities? | Event holder |
| What information should different users be able to see? | IT Specialist |
| How many ways to register should left in the software (e.g. only via emails or only via emails and phone)? | Organization addmission |
| What privacy and security requirements might apply? | Organization addmission |
| How are volunteers matched to activities? | Organization addmission |


## Stakeholders:
  - Testers: Need a clear test cases for the software with clear evidences to verify that everything work as required
  - Volunteers: Need a software where they can register for event via one register system, see what skills required and other info about event
  - Event organiser: Create and manage events, see availability, skills, registrations and attendance; contact relevant volunteers
  - Organisation Admission: Needs a software to maintain volunteers show them data about events and show them information they require
  - Developers: Needs a clear explained requirements with what and how should work and be realized

## Candidate Requrements:
  - Functional
    - System shall show available events that needs volounteers
    - System should have a clear UI that does not require any instrunctions and native to use
    - System should store volounteer information in one place
  - Non Functional
    - Constrains( Privacy and Security) - Only admins and event managers should be able to see who applyed for event  and have their information to contact them - Some personal data should be encrypted to prevent leak of personal information

## Requirements Surgery:
  - R1
    - Weakness: Dosen't specify type of events and how many of them are handling through the year
    - Rewritten: Organisation provide an iformation about sports/shops/music events that require volounteers and handlig around 70 events through the year 

## Goals:
  - Provide one system registration for events
  - Show available events to volounteers 
  - Provide information about events e.g. time, place, skills requred, etc.
  - Provide information about volounteers to events managers

## Scope:
  - # In Scope
      -  volunteer account/profile management
      -  skills and availability
      -  event creation and maintenance by authorised organisers
      -  event browsing and details
      -  volunteer registration and withdrawal
      -  eligibility checks against event requirements
      -  attendee lists for authorised organisers
      -  event update/cancellation notifications
      -  attendance recording; role-based access
      -  privacy and accessibility controls
  - # Out of scope:
      - Payroll
      - Volunteer expense claims
      - Fundraising
      - Public event ticket sales
      - Background-check processing
      - Full learning-management system
      - Integration with external email/SMS providers beyond sending notifications
 
## Use-Case

# Functional requrements
  - System shall show available events that needs volounteers
  - The system shall allow a volunteer to create an account using a unique email address.
  - The system shall allow an authenticated volunteer to view and update their contact details, skills and availability.
  - The system shall display published events with date, time, location, activity description and help/skill requirements where provided.
  - The system shall allow an authorised organiser to create, edit, publish and cancel an event.
  - The system shall allow a volunteer to register for an available event.
  - The system shall allow a volunteer to withdraw from an event registration.
  - The system shall compare a volunteer’s recorded skills with the skills specified for an event
  - The system shall allow an authorised organiser to view the registered volunteer list for an event.
  - The system shall allow an authorised organiser to record whether a registered volunteer attended an event.
  - The system shall send a registration confirmation to the volunteer’s registered contact channel.
  - The system shall notify registered volunteers when an organiser changes or cancels their event.
  - The system shall allow an organiser to send a message to all registered volunteers for an event or to a selected subset.
  - The system shall prevent a volunteer from registering for an event when a required skill is not recorded, unless an authorised organiser overrides the restriction.
  - The system shall allow an organiser to search or filter volunteers by recorded availability and skills.
# Non-Functional requirements
  - The system shall restrict personal volunteer information and attendee lists to users with an authorised role.
  - The system shall collect only personal information necessary for volunteer coordination and display a privacy notice before account completion.
  - The system shall support keyboard-only operation and provide programmatic labels and text alternatives for interactive controls and meaningful images.
  - The system shall present its main volunteer tasks in a responsive layout usable on mobile, tablet and desktop screen sizes.
  - For normal operation, the system shall display event search results within 3 seconds for up to 500 concurrent users.
  - The system shall maintain an audit record of event creation, material changes, cancellation and attendance updates, including actor and timestamp.
