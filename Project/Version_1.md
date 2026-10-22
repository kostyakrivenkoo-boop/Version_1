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
  - Testers: Need a clear test cases
  - Volunteers: Need a software where they can register for event via one register system, see what skills required and other info about event
  - Event organizations: Needs to see how many volunteers registered
  - Organization Admission: Needs a software to register volunteers show them data about events and show them information they require
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
      - Mixed booking system
      - Organisators doesn't know who attends the event
      - Volounteer's information stored in several places
  - # Out of scope:
      - Who is creating events?
      - What happens if volounteer cancels?
      - Who can register as a volunteer?
      - What accessibility requirements should be considered?
 
## Use-Case

# Functional requrements
  - System shall show available events that needs volounteers
# Actor
  - Volounteer. Volunteers are a core external user group defined in the scenario.
# Actor's Goal
  - To find information about available events that require volounteer

