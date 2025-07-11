# Example Issue Created Using Templates

This is an example of what an issue would look like when a teacher fills out one of our templates:

## Example: Add New Activity Template

**Title:** [New Activity]: Photography Club

**Activity Name:** Photography Club

**Activity Description:** A club for students interested in learning photography techniques, editing photos, and showcasing their work. Students will learn both digital and film photography, participate in photo walks around campus, and organize exhibitions of their work.

**Activity Category:** arts

**Meeting Days:** Tuesday, Thursday

**Meeting Time:** 3:30 PM - 5:00 PM

**Maximum Number of Participants:** 18

**Special Requirements or Equipment:** Digital cameras (school has 10 available), photo editing software on computers, darkroom access for film development, storage space for displaying student work

**Teacher Sponsor Information:** Ms. Anderson (Art teacher with 5 years photography experience, personal studio photographer on weekends)

**Additional Context:** Several students have been asking about photography opportunities. This could tie into the yearbook committee and school newspaper. Would like to start this fall semester.

**Acceptance Criteria:**
- [x] Activity should appear in the activities list on the website
- [x] Students should be able to register for this activity  
- [x] Activity should be filterable by category and day
- [x] Activity details should display correctly (description, schedule, max participants)
- [x] Teachers should be able to see registered students for this activity

---

## Why This Works Well for GitHub Copilot

This example shows how the template guides teachers to provide:

1. **Clear problem description**: "Add Photography Club with specific details"
2. **Clear acceptance criteria**: Checkboxes define exactly what success looks like
3. **Hints and context**: Equipment needs, teacher experience, timing preferences
4. **Limitations**: Equipment constraints, participant limits, space requirements

A GitHub Copilot coding agent can easily understand:
- What to add to the database (new activity entry)
- What fields to populate (name, description, schedule, etc.)
- What to test (registration, filtering, display)
- What constraints to consider (equipment, participant limits)

The structured format eliminates ambiguity and provides all necessary implementation details.