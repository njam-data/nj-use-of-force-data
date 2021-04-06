# nj-use-of-force-data

- [Article with background info](https://www.nj.com/news/2021/04/nj-releases-data-showing-every-time-cops-hit-tackled-or-shot-suspects-on-groundbreaking-new-website.html)
- [Announcement from NJ Attorney General](https://www.njoag.gov/force/)
- [Data source](https://njoag.app.box.com/s/upgf6yyi9g0fyjg6ednhqmr69dg9crfh)
- [Previous nj.com use of force project](https://force.nj.com)

## Data columns

> [Source](https://njoag.app.box.com/s/upgf6yyi9g0fyjg6ednhqmr69dg9crfh/file/796093170307)

|field_name|definition|multi_select|
|----------|----------|------------|
|unique_report_id| Unique ID identifying report||
|report_number_portal| Report number generated for the agency within Use of Force Portal||
|incident_id| Unique ID to identify reports of a common incident using agency specific internal agency case numbers||
|county| County of agency||
|agency_name| Agency name||
|incident_case_number| Internal agency case number||
|incident_municipality| Municipality of the incident location||
|incident_date| Date of incident||
|incident_date_utc| Date and time of incident‐coordinated universal time||
|contact_origin| Origin of the contact type| true|
|incident_type| Type of incident| true|
|location_type| Type of location| true|
|indoor_or_outdoor| Indoor or outdoor incident||
|incident_weather| Weather conditions||
|incident_lighting| Lighting conditions||
|video_footage| Is there video footage?||
|video_type| Type of video footage| true|
|officer_name| Officer name||
|officer_race| Officer race||
|officer_age| Officer age||
|officer_gender_fill| Officer gender||
|officer_rank| Officer rank||
|officer_in_uniform| Was the officer in uniform?||
|officer_injured| Was the officer injured?||
|officer_injury_type| Officer injury type||
|officer_medical_treatment| Officer medical treatment| true|
|officer_hospital_treatment| Status of hospital treatment for officer||
|other_officer_on_scene| Were other officers on scene?||
|subject_type| Type of subject||
|subject_race| Race for each subject||
|subject_age| Age for each subject||
|subject_gender| Gender for each subject||
|subject_transgender| Subject identifies as transgender||
|subject_perceived_condition| Perceived condition for each subject| true|
|number_subjects_injured_in_incident| Number of subjects injured in force incident||
|number_subjects_injured_prior_to_incident| Number of subjects injured prior to force incident||
|subject_injury_type| Subject injury type| true|
|subject_medical_treatment| Type of medical treatment for each subject| true|
|subject_arrested| Arrest status for each subject||
|reason_subject_not_arrested| Reason subject not arrested for each subject||
|type_of_force| Type of force officer used| true|
|subject_actions| Actions leading to force for each subject| true|
|subject_resistance| Type of resistance for each subject| true|
