Pivotal Labs Design Technique: 
#Think-Aloud Thursdays
Francisco Hui, Winter, 2014

---

What is 

## Think-Aloud Thursdays (T.A.T.)?

- Weekly Usability Sessions
- Much shorter than regular usability tests
- Builds habit of getting work in front of users

---

## How do we do T.A.T.?
- Recruiting and logistics is handled by SF and NY design team
- Because they're short, they're cheap: not a lot of prep work

---

## Why do we do T.A.T.? (Goals)

- Validate usability of interface: Can people use it? 
- Validate value prop of product: Do people want it?

---

## Effects of T.A.T.
- Become more *confident* in design decisions
- *Communicate to client* why make certain design decisions

- If the client has tested design, this complements the schedule: TAT is faster and shorter
- If the client hasn't tested design, this makes them think about it and put things in front of users

---

## Before
- Prep the thing we're testing: paper prototypes, Flinto/InVision clickthroughs, etc.
- Write scripts or questions

---

## Prepping the User

- Prep user: "We're testing the app, not you. Think aloud"
- Start talking to user. Are they familiar w/ space you're working in? 

- If mobile: ask them whats on their phone
- Ask them about the domain

---

## Giving the test

- Scribe is writing notes; 
- Audio and video recording depending on documentation for stakeholder
- Interviewer is taking mental notes
- Session lasts 15-45m
- 2-3 users per week
- In total: ~90m for 3 users

---

## After
- 5m debrief internally w/ each session

> 
- What did we notice? What jumped out?
- After all three sessions, digest more in-depth

---

## Two Things Can Happen
- w00t! or
- oh shit!

- If the team is churning or trying to make a decision, this can help decide using data

---

# Example

- Send-flow: need to choose the contact
- How do users think about selecting a contact?
- 1st version: default iOS contact screen
- Problem: no affordance to tell users what to do ("Pick a contact")
- Next iteration: inline search; as you start typing, a list of contacts gets filtered
- Alternative: look-ahead, when you tap on a name then you get a modal of contact points (email addy, phone number) for that person
- Two new iterations were better than first, but same as each other
- Modal view was slightly better

---

## "How is Such a Small Sample Size Useful?"
- If all 3 users do the same thing, confidence increases
- You can start predicting what people will do given the same task
- Samples size becomes moot if you're consistently successfully predicting behavior


---

# Goals
- Train clients and team to get feedback from non-team members
- Get real feedback to inform design decisions 
- Lead-in to more robust testing (when appropriate)

# Risks
- Stopping here at usability testing (and not going deeper into Product Validation), esp for products w/ specific user population (e.g. doctors, traders) rather than more general B2C apps.
- Waste of time and money if you don't gather new learnings
- Small rough tests could mislead due to poor test fidelity


---
<script src="js/impressConsole.js"></script>
<script src="js/jquery.js"></script>

<script>
  $(document).ready(function(){
     $("ul").wrap("<div class='notes'></div>");
     // $("li strong").wrap("<div class='notes'></div>");
     impressConsole().init();
     // impressConsole().open(); // for console to open automatically
   });
</script>
