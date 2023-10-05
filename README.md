# SQLquestion30
Can we disable a trigger? If yes, how?


 Yes, we can disable a trigger in PL/SQL. If consider temporarily disabling a trigger and one of the following conditions is true:

An object that the trigger references is not available.
We must perform a large data load and want it to proceed quickly without firing triggers.
We are loading data into the table to which the trigger applies.
We disable a trigger using the ALTER TRIGGER statement with the DISABLE option.
We can disable all triggers associated with a table at the same time using the ALTER TABLE statement with the DISABLE ALL TRIGGERS option.
