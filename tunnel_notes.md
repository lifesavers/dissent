Dev Tunnel Notes
=================

DISSENT Chaperone - Minimal Viable Service
------------------------------------------
ASK Reverse synthesis

Basecamp -3
1. Generate JSON Object for PagerDuty
2. Mock JSON Object (Mock Room, +Learner Status, +Trial Arm) with node.js Lambda Code Chaperone Shuttle
3. Test to satisfaction on 'DISSENT' Chaperone minimal trigger
4. DynamoDB Table set-ups:
- resus (device_id, calmunity, courtoptionlist[+TTL], courtbackoptionlist[+TTL], uniqueunlock (sageword), apologiesrfplist[+ParkinsonLawTTL], how_to_say_i_jet'aime, how_to_say_j'adore, how_to_say_us [schemaless list of schemas], enthrall_flag, nukecall_rate, gpcall_rate, sex, gender, [calmunity_safewords], mediarules, address, lastaddresschange (date), relationlock, ...., (latest), driver_status, [incident_key])
- incident logs (calmunity, incident_key [device_id], EtOH_test, blob_report, report1, report2, report_obs1X, report_obs2Y, resu_guid_innocent1, resu_guid_innocent2, schemaexception_report)
- calmunity (stopword, safeword, nonsexual_conflictsageword, fireprocess_consolidatedcode, firedissent_calmunity_warnningnote)
- devices (device_id, term_of_activity, [resu_guid])
- healthwarn (resu_guid, device_id, status, last_update, expiration, provider_pointer, accesscost) [update every 24hrs]
- sagecount (device_id, period_state, week, month, year)
- gruewarns (resu_guid, device_id, privacy, expiration, counsel_cue)
- dissentwarns (resu_guid, device_id, privacy, expiration, counsel_cue, [address], [lastaddresschange])
- sleepdebt (resu_guid, device_id, [calmunity], [house], steep_start1, steep_end1, steep_start2, steep_start2, steep_start3, steep_end3, steep_start4, steep_end4, steep_start5, steep_end5, steep_start6, steep_end6, rest_start7, rest_end7, last_week, this_week, wake_time1, wake_time2, wake_time3, wake_time4, wake_time5, wake_time6, nowake_time7, nowake_restday [driver_status], driverwarn, driverpps, highway_parentstretch_assign_yearstretch)
- lockerroomtalk (resu_guid, sage, age, statement, perceived_likert_threatlevel, witness, witnessreport, witness2, witness2_report, witness3, witness3_report, witnessN, witnessN_report, recreation, recreation_report, recreation2, recreation2_report, validation_state, counsel_delivery)
- couples_last (relation, relationlock, courtoptionset[+TTL], flirtercheckclearance[no record: we don't know, goask, heres_how], enthrall.ed_multilaterals)

1 nothing 
2 quite_oversensitive "Man, ¿15 minutes? Por que? Are you on Hh Standard Time?" - Fellow Hh, chiding me about :18 minute offset3 friendly_banter
4 lightmid_stagecomedy_freespeech_noofficialapologyrequired "Man, ¿15 minutes? Por que? Are you on Indian Standard Time?" - Indian, chiding another about :18 minute offset3 friendly_banter 
5 heavy_stagecomedy_apologyoffer "Nigga" said outside Path Putonghua Spacing Studies (i.e. 'uhh...') _____ 
6 unacceptable_unaccountable_hatespeech "Nigga" said outside Path Putonghua Spacing Studies
7 prosecutable_incitement_crimeplan_hatespeech "Grab them by the pussy, present and past tense"

Note on Nigga: No other ethnic group says such a thing within as a 'term of endearment by peer circle and inadvertant eavesdrop staining diminuition'. No Hh Jew says to another Hh J "Hey, my kike". No one does that. If they did, whether or not anyone was within earshot, we would go livid on each other, and it would not happen again, whether in private or out in public, Kike is just entirely off-limits, a review of the indignities of the langauge's socially discriminatory past. No one says kike. Hardly anyone even knows what it means anymore, because we shut it down. No Hh Hispanic says "Hey, my spic." No one does that. No one. There's no comparable, anywhere, to "Hey, my slave." So what is this? Why is this made and considered acceptable among children? Why isn't this locked out of classrooms, outside of, say, studies of the book "Nigger" (which struck me as wonderful for high school, for the record)? "Nigger" will take a century or more to go the way of kike and die. We'll know what it is as we study HSTRY and film. But it won't be on the tip of anyone's tongue if we extinguish it at 5 and 6 now. I call 6. Let me be really clear, and get to the heart of the calmunity: I call 6 on Jay-Z. I think Beyonce calls 6 on Jay-Z.  Jay-Z doesn't need to turn into Will Smith to make art. Although, honestly, Will Smith is a really good artist, and a really good father, and that comes out in music that has no f-words at all, and has always been clean. i think we should all recognize that: Will Smith had choices, and went for all neighborhoods. We can argue about the emancipation of Jayden early, maybe. It's an interesting topic. But can anyone argue that Smith is not an exceptionally artful and devoted father? But Will Smith had children back before Miami. Jay-Z just had a child. What kind of langauge will Blue have? I ask the same thing intensely all the time about Delta, and it does change everything having someone you're passing the world over to. The only reason i'm doing this is because it needs to be done: it requires one public critique of one central Pilla of "Nigga" to internally sabotage the foundations, and Jay-Z is with Barack Obama the best Person, and Jay-Z and Beyonce (with Michelle and Barack Obama) are without any question the best couple on Earth to take the word "Nigga" down concertedly, outside of its dated HSTRYical and Period film context. Ok, that period film work now extends to the last season of 'The Wire' (02008), maybe a little further. I saw it in 02014 in Public Schools, and got fired (from a whole region of schools at once, before the Principal even spoke with me) for fighting it. It doesn't have to go any further.

Basecamp -2
1. Add payload handling code for DISSENT READY, DISSENT SET
2. Generate JSON Object Alert iteratively from tables, with Response Pattern, Alert Intensity Dynamically, with Simple resus Table Pulls, writeback latest incident-key to resu table on overwrite and uniquely to incident log, Lowest Latency Search

Basecamp -1
1. Test prove remaining DynamoDB, Lambda, device_id, and resu exchange sufficiency within Amazon ecossys, without external https:// endpoint
2. Reedit db tables with findings
3. Build db entry sequence system on ASK device_id set-up, Camtasia advised Admin experience at this early test of the test-pilot stage, requiring here manual or voice-assisted observed device_id entry confirmations
4. Test ASK set-up on number of Echo Devices to desired JSON Object, test rapidity of resu entry prep and load, press for 5m or less on arbitrarily hard resu info available with presorted init healthlog exchange or health entry post-process within 30 (University) - 90 (City) preventive days
5. Test push JSON to PagerDuty with range of "READY", "SET", "GO" / "MANGO" Codes

Basecamp 0
0. Write incident_key back to device_id table for ongoing incident management updates
1. Set up prep layer based on Housing Calmunity Complex, with basic+ error-checking of room entries
2. Set up map between Calmunity Complex and Responders Union in PagerDuty Branches
3. Verify actuation in 1.869s or less, measure alert times carefully, pull down as close as possible to 1.869s with ASK/Lambda/PD Infrastructure
4. Prepare Seamless Court Demo on Reckless Conduct, given any Phone #, Email Address, with timing variances described

Not necessarily complete, but a good starting point for some of the more time consuming dev_tunnels on the ASK MVS.

Basecamp 1
- Systematic Entry Validations on Launch Tables
- Systematic Default Loads on Launch Tables
- Calmunity MDM Models, MDM Entry Interface (Start with Assuming IT Service Expertise, admin webapps at this point, assume relatively high precision or human validation, forced duct tape on Trust DISSENT on Calmunity MDM_PagerDuty Set-up match)