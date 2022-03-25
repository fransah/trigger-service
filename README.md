# trigger-service

This project is used to trigger other repositories to do their component test.

The 'Trigger Test' workflow can be kicked of manually by a button.

This will trigger 'trigger1' and 'trigger2'  repositories.

These repositories will post back a result to the trigger-service which will handle the events and turn red or green.

trigger1 repo should pass the test.  
trigger2 repo will fail.

It can be cleaned up a bit, but it shows the principle should work.