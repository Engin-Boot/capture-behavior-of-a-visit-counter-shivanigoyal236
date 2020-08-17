# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given a computer that is on
  When  a visitor visits the hospital we give him an id card
  and if goes out and in multiple times he would be counted as one
  Then we can keep track of id card issued in a day in our
  computer and can get visitor trends during a week of operation

Scenario: Alert when seating capacity is full

  Given a sensor that senses head of person and a computer that is on
  When a person enters in seating area then sensor senses the person
  and add it to computer and when he comes out then it subtract him
  so when no of persons is equal to the no of seats
  Then computer alerts that seating capacity is full
