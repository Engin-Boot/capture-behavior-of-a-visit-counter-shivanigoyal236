# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given a computer that is on
  When a patient visits the hospital
  we issue him a id card and keep the data like id number
  registration day on our computer in a excel sheet
  Then we can count visits of patient during working days
  and holidays from excel sheet

Scenario: Compute parking slots to reserve for visiting specialists

  Given sensors and a app for parking facility of hospital
  When someone parks his car in parking space then sensor senses
  the car and we can take a variable count that has starting value
  is equal to parking spaces available in area when sensor senses the
  car it subtract count by one  and same if someone
  take out his car from the space then it increase the count by one
  Then by this count we can always know the free parking slots 
