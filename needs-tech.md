# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter

  Given a computing device
  When server goes down restart it
  Then save all the data

Scenario: Reconcile counts if the sensor is offline for a while

  Given a computer
  When sensor is offline we manually count
  Then update the count in computer
