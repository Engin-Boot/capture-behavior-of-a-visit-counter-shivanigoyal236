# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  given a id generating system with time stamp connected to visit counter
  when a patient enters in hospital
  then it shows visits during working days and holidays
  
Scenario: Compute parking slots to reserve for visiting specialists

  Given sensors that detect vechiles entering in parking area and
  an app for parking facility of hospital
  When someone parks his car in parking space
  Then we get details of space on app
