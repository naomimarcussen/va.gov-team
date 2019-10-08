# Research Plan for Authenticated Experience/Personalization: Address Override

## Goals
1.  **What product & team are you doing this research for?**

Address Override.  Authenticated Experience/Personalization.

2.  **Background: Briefly, what is the background on this product? What would a new person on the team need to know about this product?**

Vet360 is providing Address Validation.  There are several situations where the Veteran will need to make choices in order to properly select a more accurate address option or to override provided options.

This is sometimes due to the situations where Pitney Bowes Spectrum address database has not yet caught up to the cartographical realities of the US housing market,  and the Veteran should be able to confirm that "yes, this is actually a real address."

This Address Override feature requires UX in various places to allow the Veteran to complete their address edit workflow easily and accurately.
  1. Veteran enters accurate address.  If the entered address matches the database address with the highest Confidence Score, the updated address displays on the UI.
  2.  Veteran enters inaccurate address.  The UI will display the entered address and up to 3 address suggestions and allow the Veteran to edit the entered address or the Veteran is required to select 1 address to continue to complete the update.
  3.  Veteran eneters inaccurate address that the database cannot identify.  The UI will display the entered address with no address suggestions and allow the user to edit the address or continue with the address override.
  
  We have clickable prototypes that map out each of the mentioned UX scenarios and we need user testing to answer several questions regarding the usability of the workflow and UI.

3.  **Research questions: What question(s) do you hope to be able to answer after completing this research?** 

- Is the messaging clear to the Veteran about their entered address if the system does not recognize it?
- Is it clear to the Veteran on how to proceed by selecting their entered address or an address suggestion?
- Is it clear to the Veteran what to do when the system has no address suggestions to display?
- Is it clear to the Veteran on how to edit their entered address?
- Is it clear to the Veteran that they can go back to the address suggestion screen before they confirm the address update?
- Does it cause the Veteran any confusion if the 'Continue/Update/Cancel' buttons on the mobile form?
- Is it clear to the Veteran that the address has been updated or cannot be updated?

4.  **Hypothesis: What is your hypothesis for this research?**

- Veterans will understand how to edit their mailing address from their profile
- Veterans will understand why we display the alert if the system does not recognize their entered address
- Veterans will find it easier to make a choice if we select the best address suggestion option by default
- Veterans will be able to complete the process and feel confident their address has been updated


## Method
1.	**What method of research are you planning?** 
  
Usability testing with high fidelity prototypes.  Will have the user share their screen and walk through how to update a 
mailing address.This testing will be done remotely.
  
2.	**Why this method? How does this methodology help you answer your research questions?**

This usability testing will help us understand if there are any pain points or confusing elements to the 'update mailing address' workflow and how we can better optimize the UX.

3.	**Where are you planning to do your research?**

This research will be done remotely, using GoTo Meeting.

4.	**What will you be testing?** *(Design mocks, card sort, prototype, page, content, etc.)* 

Updating the mailing address from a profile screen using clickable, high fidelity prototypes.

5.  **If remote: What tool do you plan to use**

GoTo Meeting

## Participants and Recruitment
1.	**Participant criteria: What are you looking for in a participant?**

- People who use Va.gov
- People who have updated their mailing address on the Va.gov profile
- People who may need to update their address in the near future (or have recently updated it) on another system (Post Office, etc)

We would also like at least one participant that is:
- A female
- A person of color
- Under 40

2.	**What is your recruitment strategy?** 

We will work with Perigean to recruit for this research study.

## When? 
1.	**Timeline: What dates do you plan to do research?** 
TBD based on remaining technical discovery of the feature

2.	**Prepare: When will the thing you are testing be ready?** 
TBD - Design are completed but may change slightly due to technical discovery this week.

3. **Length of Sessions: How long do you estimate each session will be?** 

10-15 minutes per session.

4.	**Availability: If applicable, when would you like sessions scheduled?** **Please list exact dates and times in EASTERN Standard Time**. 

TBD

5.	**Pilot: Please indicate a date before your sessions begin for piloting your research. Which member of the design team will you pilot your research with?**

2 days before research sessions begin.

## Team Roles
Please list the people who will be serving in each role. **Include the primary phone number for moderator and the emails for moderator, notetaker, and observers. If you need Perigean to take notes for you, indicate that next to Notetaker** 
- Moderator: Arthur Green
- Research guide writing and task development (usually but not always same as moderator): Arthur Green
- Participant recruiting & screening: Perigean
- Project point of contact: Arthur Green
- Participant(s) for pilot test: N/A
- Note-takers: TBD
- Observers: Justin Pickett, Erik Hansen, Samara Strauss, Lisa Koenigsberg, Lihan Li, Amen Ra

**List email addresses for those who should attend and observe the sessions: VA Stakeholders, engineering team members, design team members, any other people who might find this research relevant to their work**

## Resources
- Project Brief: 
*Project brief should live in the appropriate vetsdotgov-team product folder, simply paste a link to it here*

- Discussion Guide
*Discussion guide should live in the appropriate vetsdotgov-team product folder, simply paste a link to it here*

- Notes & Recordings
*Session notes and recordings should live in the appropriate vetsdotgov-team product folder, simply place links to them here.*

- Synthesis
*Link to any documents used for synthesis (Mural or Realtimeboard boards, excel sheets, other data outputs, etc.)* 

- Lessons Learned
*Did you have any takeaways from the process of this research round that you want the team to remember for the future? Document them here.* 

- Read-Out/Results
  - *Read-out presentation should live in the appropriate product repo and folder; paste a link to it here.* 
  - ** Don't forget to add a link to your research folder to the research tracker! [https://github.com/department-of-veterans-affairs/vets.gov-team/blob/master/Practice%20Areas/Research/Research%20History.md](https://github.com/department-of-veterans-affairs/vets.gov-team/blob/master/Practice%20Areas/Research/Research%20History.md)