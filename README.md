caseTime 
========
Created By: KC Shafer

Version - 1.0

Published Date - 09/12/2012

Description - Trigger and Class to check if a case is created within defined business hours, in this case 8 -5 monday through friday.
Then either sets the custom case create date and time to now, or to 8:00 am of the closest business day. Also checks if the case 
is being created on a holiday. The trigger is not bulkified at the moment but will be in the future. Also, because this 
trigger operates on the created date, it is not possible to write a test class for it.