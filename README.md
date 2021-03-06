# TreatmentJournal

![logo](/dev/logo_trimmed.png)

(TreatmentJournal.net - not live)

On the same night that I graduated from AppAcademy, a fullstack web development bootcamp, I received a call informing me that I have lymphoma. As I spent the next 24 hours searching for information, trying to wrangle doctors, appointments, and treatment options, I quickly realized that I needed to come up with a good system to organize all of these aspects of my upcoming battle.

Also seeking a project to continue my growth as a programmer and software developer, I thought it might be a fun (and helpful) problem to tackle this organization challenge with my new skills. A bit of research revealed that patient self-monitoring is said to be beneficial to anyone fighting an illness, and potentially beneficial to medical providers as well.

----
## What problems am I trying to solve?

- Telling people that I'm sick (I'm already tired of having the same conversation on the phone)
- Keeping everyone up to date with changes and the latest details
- Keeping track of my symptoms, weight (daily log)
- Keeping track of all the different doctors and locations (sync with calendar and google maps?)
- Notifications of appointments, medications, etc
- Sharing things my partner and I need or that people can do for us
- Track treatments over time
- Upload recordings of doctors meetings, call log (who, when, what was discussed)
- What medications/doses were taken each day
- Option to share treatment/symptom data with researchers?

----

## Features
- authorization and Authentication
- search on the home page for patients
- each patient gets their own public and private pages
- Patient, caregiver, and visitor roles
- Public pages:
  - display updates
  - subscribe to update options (to get emails when things are added)
  - how you can help
- Private pages have several tabs:
  - Post update
  - Daily Log (symptom, meds, treatment, journal)
  - Listings of providers (docs, locations)
  - Agenda (List of appointments that connects with gcal, plus recaps for each appointment that can be in text, or you can upload audio files of the meeting, notifications for meds or appointments)
  - search that goes through logs, agenda items/recaps, providers, and updates

----
## Notes
  - https://www.caringbridge.org has some aspects to emulate

----
## Potential Tools:
- Ruby on Rails
- File upload gem: https://github.com/janko-m/shrine
- Do I want to do a redux/react front end for this project?
- Possible shortcut to react on rails? https://github.com/shakacode/react_on_rails
- Authentication, Devise:  https://rubygems.org/gems/devise/versions/4.2.0
- Authorization for roles (doesn't do authentication), Pundit - https://github.com/elabs/pundit
- Google Calendar API: https://developers.google.com/google-apps/calendar/
- Google sign-in: https://developers.google.com/identity/#google-sign-in
- Mailchimp API for messages? https://developer.mailchimp.com/
- Rich text edit (if I use react) - https://draftjs.org/
- Rich text edit (if only rails) - https://github.com/basecamp/trix and https://github.com/maclover7/trix
- Rich text edit if I want TinyMCE (https://medium.com/@NishL/how-to-add-a-wysiwyg-editor-to-your-rails-app-be56d8e8add6)

----

## Styles/Colors/Fonts

- logo font: Raleway
- Red: #9b1111
- Black: #000000
- White: #ffffff
- Dark Green: #3B3D1F
- Mid Green:#727E47
- Light Green: #B3BE8C
- Maroon: #2D180E
- Brown:#B29565

![collage](/dev/collage.png)
