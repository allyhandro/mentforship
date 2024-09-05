# Mentforship
Find the mentor meant for you! A program that takes google forms intake data, and performs a weighted matching algorithm based on shared interests, skill / comfort level, and other preferences like special interests or lived experiences (ie. LGBTQ, disability, neurodivergence)
___
# Run the Container
`docker-compose up build -d`

## WIP Matching Implementation
[whiteboarding](https://whimsical.com/mentforship-matching-whiteboarding-Qocue4he1K1aog1SA6Qhuv)

___
# Mentorship Concepts
The Mentforship framework of technical Mentorship operates under the assumption that we can all teach and learn from one another, no matter what our seniority. Participants are allowed to fill either mentee or mentor roles non-exclusively to encourage development of Mentoring skills earlier in the career, and continuous learning for those later in their careers.

### Skills and Practices
Each round of mentforship, participants select their ranked choice of **focuses** for mentorship.

Focuses are split into **skills**, the hard technical skills used to work in tech, and **practices**, the soft skills and concepts behind workflow, architechture, leadership, management, etc. Participant pairings with a **skill focus** are encouraged to create a small working project or Proof of Concept together. Participant pairings with a **practice focus** are encouraged to meet frequently to allow for thorough exploration of the topic via conversation. 

The separation of **skills** and **practices** also allows for the identification of talents and skillsets that do not fall strictly within the bounds of technology, like identity based experiences--such as of navigating the Tech Industry as a person of color, as someone with a disability, dealing with ageism, etc. 

--
# Running a round of Mentforship
## Step 1: Intake
Participants fill out a form indicating the role(s) they are open to (Mentor, Mentee, or Both) and what they would like their **focus** to be for the round of Mentorship.

### Mentee Intake
After electing their preferred role, each participant can select up to 3 **skills** and up to 3 **practices**. For each skill, the Mentee should indicate their **expertise** on a scale of 1 to 3, 1 being a novice, 2 being a beginner, and 3 being intermediate. This encourages peer mentorship, as sometimes it's easier to learn from someone right ahead of you than it is an aged master.

### Mentor Intake
If the participant is open to the Mentor role, they will need to additionally select up to 3 focuses to teach, as well as their relative **expertise** on a scale of 1 to 3, 1 being intermediate, 2 being advanced, and 3 being expert.

Mentors are required to answer to their availability, as Mentors may have more than one mentee.


Skill and Practice lists should be catered to your team's stack and area of expertise, and may even include institutional, org specific knowledge. It is also recommended to include freefill questions to gauge if participants have a desire to learn something unlisted. Changes to the focus list are expected over time.

([See Example Intake Skills and Practices here](https://docs.google.com/forms/d/e/1FAIpQLSebKhW5bGSWGeQe84dIS3OlagNi3XRysBW6wq3eEP8mQl2eiA/viewform?usp=send_form)) 

Fell free to make a copy of the above form and update the accepted list of skills and practices as needed. 


## Step 2: Matching
Mentforship implements the [NRMP algorithm of matching](https://www.nrmp.org/intro-to-the-match/how-matching-algorithm-works/), used to match medical residents with the best match of residency programs.

Mentforship's Matching Algorithm is "mentee-proposing" and attempts to pair a mentee with the mentor with the best match of focuses. 
