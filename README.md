# ICE12Test
Updated draft YAML for ICE 12 Testing. Includes corrected log event schema with duplicate incidentID fix.

Started with Henry Unger's Commit "Update loggingservice.yaml to remove conflicting incidentId per Michael Smith errata against EIDO Conveyance v1.0 #18", then manually edited in changes from Michael Smith commit:
"Fix duplicate incidentId problem in loggingservice.yaml per STA-010.3b #19"

Did NOT make the changes from the following outstanding commits because they don't affect ICE 12 testing:
* dmongrain - Fixed typo in required element name #16
* dthvt - Title case corrections on return values #15
* rpastro - fix: Correct schema definition for IncidentIdArray #4
