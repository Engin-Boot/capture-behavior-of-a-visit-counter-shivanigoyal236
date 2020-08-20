# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given a id generating system that is connected to visit counter
  and a report generation system
  when a visitor visits the hospital
  then we get the all information in a report

Scenario: Alert when seating capacity is full

  Given a sensor that senses head of person and connected to visit counter
  When a person enters in seating area
  then it alert how many seats are left
