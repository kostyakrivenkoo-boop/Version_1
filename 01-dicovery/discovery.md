# Week 1 - Initial Discovery
## 1. Facts
 - Equipment can be double-booked
 - Sometimes booking is unclear
 - Staff checks booking manually
 - Sometimes equipment not returned in time
 - Students not sure who contact about booking
## 2. Assumptions 
  - Equipment can be booked for certain amount of time
  - Booking available only in certain time
  - Contact for booking required
  - Know amount of equipment
## 3. Unknowns
  - Maximum booking time
  - Time limits when equipment can be booked
  - Who can book equipment
  - Booking system e.g. emails
## 4. Stakeholders
  - Students: Availability, easy booking 
  - Staff: Equipment, booking timetable
  - Developers: Certain tasks and requirements
  - Testers: Certain cases e.g. double-booking, book for longer time then available, etc.
  - Collage: Certain result that will be stable
## 5. Goals
  # The system should help the collage to:
  Mainly
    - Achieve easier booking
    - Provide booking times
    - Unite booking system
## 6. Scope
  # In scope:
  Likely to be problem
    - Double-booking
    - Who can book
    - mixed booking system
  # Out of scope
  Not yet established
    - How much of equipment available
    - Who to contact about booking
## 7. Candidate Requirements
  # Functional
  The system shall
    - Provide clear availability of equipmets
    - Be 
    - Provide amount of available equipment
    - Allow an authorised user request equipment for a specified date and time
  # Non-Functional
  Constrains( Privacy and Security)
    - Only admins and collage managers should be able to see who booked an equipment and have their information to contact them
    - Some personal data should be encrypted to prevent leak of personal information
## 8. Requirements Surgery
  - R1:
      - Weakness: Doesn't explaining what easy means, doesn't specify easy for whom, how we understand when it's easy enough
      - Rewritten: The system should provide clear booking system that can be used straight away and provide easy navigation through system
  - R2:
      - Weakness: Doesn't specify which aspects should be secure, which way it should be secure, what 'secure' means in that case, how we can verify that data saved securely
      - Rewritten: System should protect data which means store it privately, encrypt vulnerable data such as credit cards information, personal data, etc.  
## 9. Reflection
While doing this project I learned how to split task in requirements
