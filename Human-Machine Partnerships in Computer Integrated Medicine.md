---
aliases:
  - Russel H Taylor robotic surgery talk
tags:
  - meeting
author1: "[[Hendrix Gryspeerdt]]"
date: 2025-11-12T16:30:00
duration: 60min
meeting-type: Lecture
---
## Participants
- [[Russel H Taylor]]
## Materials 
- 
## Questions
- 
## Notes
- about [[Russel H Taylor]]
    - he worked at IBM research
    - one of the founding fathers of [[Computer Integrated Surgery]]
- combination of components for medicine
    - physicians
    - technology
    - information -> use for statistical process improvement
- complementary capabilities
    - humans vs. machines
    - we need to consider the entire room
- challenges
    - task specification: unambiguously tell the machine what you want it to do
    - task execution: make sure the machine does exactly what you want, nothing extra, no mistakes
- Surgical CAD/CAM
    - design treatment
    - use treatment design to design machine
- tasks
    - image assisted needle placement
- human controlled robot surgery
    - first way
    - newer ways
        - different controls, 
        - to increase precision
        - reduce hand tremors
        - safety barriers
- how to share information between surgeon and machine
    - state of patient undergoing treatment (3d model) in computer
    - digital twin
- laryngeal surgery
    - risk of severing vocal cords
- skull surgery
    - risk of nerve damage making half of head go numb
- tool controls
    - tremor reduction
    - safety barriers
- communication between human and robot
    - instrument controls
    - voice controls
- Sinus surgery
    - requires multiple hands
- Bilateral Sagittal Split Osteotomy (BSSO) 
    - type of Jaw Surgery
    - robot makes much cuts with much more consistent and precise
    - how to bolt things together after the cut
        - drill on an angle
- robotic assisted breast cancer surgery
    - scanning to detect cancer cells without cutting
- what about autonomous surgery?
    - Automating Long-Horizon Surgical Procedures
    - colleague Alex Krieger
    - current approach is to do imitation learning
    - doing Gallbladder Removal Surgery autonomously
    - limitation is that they are only doing imitation learning, it would be better if you could include some semantic data
- Retinal Surgery
    - lulian lordachita, et al.
    - Force-limited Retinal Membrane Peeling: Berc Gonenc, I lordachita, et al.
    - ... multiple more examples
    - putting a needle to dissolve a blood clot in a retinal vein
- ARAMIS: Augmented Reality Assistance for Minimally Invasive Surgery ...
    - L. Qian, X Zhang, A. Deguet, ...
- Photoacoustic Retinal Stimulation
    - Emad Boctor, et al.
- beyond the operating room
    - The Role of Robotics in Infectious Disease Crises
        - useful if a person has an infectious disease and it takes a long time for a person to put on protective equipment, then using a robot to go in there
    - Intelligent Intensive Care Unit Assistant
- conclusions on challenges and areas for future for research
    - Human Intention Interpretation: for task specification
    - Assured Action: for task execution
        - get machine learning systems to recognize when they are in a state they don't know what to do, issue with 
    - Information: focus on entire treatment cycle, statistical process improvement
        - need to measure long term outcomes for the patients, this is challenging
        - use to train new surgeons
- bottom line
    - provide new capabilities that transcend human limitations in surgery
    - Increase consistency and quality of surgery
    - Promote better outcomes and more cost-effective treatments


Questions
- first
    1. camera looking at what's happening
        - how does all other information happening in the patient (other data like bloodflow)
    2. how about someone who is technically gifted to do surgery (like 15 year old who is good at controlling robots)
        - not really a place here
        - need human judgement to make sure machine is doing right thing
        - machine enhances technical capabilities
- there were more questions but I had to leave