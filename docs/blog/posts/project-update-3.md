---
authors:
  - felicia
  - kae
  - justin
  - rafi

categories:
 - Project Update
 - CPSC 444

date: 2024-02-29

draft: true

slug: project-update-3

---

# Project Update 3

This blog post will include a revision to the task examples, information about our low-fidelity prototype and cognitive walkthrough, and more thoughts on the overall goals of our experiment. 

<!-- more -->

## 3a. Further Updated Task Examples

!!! quote "Original Task Examples"

    Task Example 1: Jeffrey
    
    Jeffrey is a biomedical engineering and experimental medicine graduate student at UBC. Jeffrey’s partner works on campus as well and he considers himself to be well familiar with general campus amenities. On days when they are both busy, they utilise UBC’s daycare service for their child. Jeffrey, his partner, and their child (Geoff) will often meet on campus after work/class before deciding on dinner plans. Geoff – being 13 months old, requires regular diaper changes. He prefers to do so in male bathrooms that have a changing table as he doesn’t like occupying the accessible bathroom unless absolutely necessary.  
    
    Jeffrey knows of 2 bathrooms on campus that have changing tables. One in his department’s building, and another close by to his and his partner’s usual meet spot. On occasion, his child will need a diaper change while he is exploring a new area of campus. During these times, Jeffrey typically opts for returning to 1 of his 2 safe bathroom spots as he is unfamiliar with which surrounding buildings have (ideally male) bathrooms with change tables, which buildings have restricted access, and where specifically the bathrooms are located within each building, etc.
    
    
    Task Example 2: Karen
    
    Karen is a parent taking photos of her son by the UBC fountain before his graduation ceremony. This is her first time on campus, so she is unfamiliar with the facilities. The ceremony is starting soon, so she wants to find a washroom nearby that she can access quickly without much walking since she is wearing uncomfortable shoes. Since it is a later in the day, she is not sure which buildings are open to the public and which ones need keycard access, such as those that are locked after a certain time. It would take some time to check each building for access and facilities, and she is not sure which one will be easiest to access for her. She can ask her son for directions, and he is able to direct her towards a building, but she does not know where to go after entering the building and needs a way to find further directions.   
    
    
    Task Example 3: Marie
    
    Marie is a new teaching staff member at UBC and requires a wheelchair to move across campus. She has not had an orientation of the buildings she is teaching in and is not familiar with where facilities are located. Marie has a very busy schedule, with lecture blocks right after each other. She needs to find a washroom between her classes that is wheelchair accessible. She also wants to find a washroom that is close to her next class but worries about washroom availability with many students also using this time to use the restroom. 

<br>



### Revised Task Examples

Two of our task examples remain unchanged, but the second task example called "Karen" has been updated slightly.

!!! info ""

    **Revised Task Example 2: Karen**

    Karen is a parent taking photos of her son at the UBC fountain prior to his wedding ceremony. This is her first time on campus, so she is unfamiliar with the facilities. As this is a private event, there are no UBC staff members that can assist. The ceremony is starting soon, so she wants to find a washroom nearby that she can access quickly without much walking since she is wearing uncomfortable shoes. Since it is a later in the day, she is not sure which buildings are open to the public and which ones need keycard access, such as those that are locked after a certain time. It would take some time to check each building for access and facilities, and she is not sure which one will be easiest to access for her. She can ask her son for directions, and he is able to direct her towards a building, but she does not know where to go after entering the building. 

We changed the context of the task example to be a wedding ceremony instead of a graduation ceremony. As graduation ceremonies typically have lots of staff and volunteers to help guide guests, we wanted to make the task example more challenging and generalized by removing this support. Also, we removed the specific details on how she completed the task to make the task example more open-ended and allow participants to come up with their own solutions. 

Other than this change, the task examples remain the same. Our task examples went through a significant update in blog update #2, and they continue to be applicable and relevant to the current direction of our designs. We currently do not have any significant updates to our requirements or methodology to justify changing the other task examples.

---

## 3b. Low-Fidelity Prototype Demonstration

PLACEHOLDER TODO: Add low-fidelity prototype demonstration

---

## 3c. Additional Information about Prototype

The chosen design of a mobile app should support all our task examples. An app provides the flexibility for it to be used on the go, making it suitable for those who have limited time to find a washroom (e.g. Marie and Karen) as well as those who have time to explore. Further, with the knowledge that UBC Vancouver provides Wi-Fi access to both guests and members of the community, a mobile app can be easily downloaded by anyone on campus. This design also accounts for different preferences for washroom features and amenities and takes measures into categorizing them for ease of use. Additionally, since a mobile application has a built-in update mechanism, the faster release cycles should enable us to quickly update any features or preferences that have not already been accounted for. This would be much more difficult and expensive with a stationary board or a custom device. 

At this stage, this prototype has both breadth and depth, but focuses more on the depth of key features. With regard to breadth of the design, wireframes for all key features have been designed. However, some less crucial pages such as the profile page were omitted. With regards to depth, we paid special attention to key aspects such as searching and viewing washroom details. Interactions on these pages are more complete and flow seamlessly between one another. 

One key design decision we made was to give users the option of a more visual or text-based interface – specifically for washroom features. This will be implemented via a toggle that allows for users to switch between an icon view of information and a text-based view of information. Another choice made was to leverage positive transfer effect and utilize industry standard interactions such as screens sliding into frame from the right after a button is clicked and swiping from left to right to return to the previous page.

---

## 3d. Cognitive Walkthrough Report

During the cognitive walkthrough, we asked participants to complete the following tasks: 

- Assuming you are somewhere on campus, find a nearby washroom as quickly as possible 
- Assuming you are at the washroom, try to add or update information about the washroom 

While the user completed the task, we were looking for the following: 

- How long it took for the user to complete the task 
- Whether the user's conceptual model matched the system's conceptual model, which is to say if the effect of the user's actions matched their expectations 
- Whether the information or button is visible and easy to find, once the user knows what they are looking for 
- Once an action is completed, can the user recognize that the action was successful and would they have benefited from any additional feedback 

The cognitive walkthrough identified several usability issues with our prototype. We found that the user was able to quickly find the washroom using the quick search button, but they had difficulty getting back to the home screen afterwards. Additionally, the user could add information to the washroom, but they said they may not have done so unless specifically asked to do so. This suggests that we may need to make the process of adding information more intuitive. 

One suggestion from the participant was to connect the process of adding information to the process of finding a washroom. Once the user has arrived at the washroom, which would either be detected automatically or selected by the user, the app could prompt the user to add information about the washroom. This would make the process of adding information more intuitive and would also help to ensure that the information in the app is up to date. 

---

## 3e. Proposed Goals of Experiment

For our experiment, there are a few goals that we would like to focus on. We have ranked these goals by importance and our ability to test them within the scope of CPSC 444. Our two most important goals are:

1. **Do users feel motivated to add/update washroom data?** 
    - This is the most important goal for our experiment. We want to ensure that the app is sustainable and that the information in the app is up to date. As such, we want to investigate whether users feel motivated to add or update washroom data. 
    - While this currently exists in a limited form in our low-fidelity prototype, we will need to expand on this for our evaluation. In particular, we want to explore different ways to motivate users to add or update washroom data. For example, we could explore the use of gamification or social incentives.

2. **Do users prefer a visual or text-based interface?** 
    - This is the second most important goal for our experiment. We want to ensure that the app is accessible and usable by a diverse set of people. As such, we want to investigate the best way to convey information, so it is easy to use.
    - This is easy to test since it is already partially implemented in our low-fidelity prototype. For our evaluation, we will ask participants to complete tasks using both the visual and text-based interfaces and then ask them which one they preferred.

We also have 3 smaller goals that we could take on if time permits:

3. **Do users value the option to switch between text-based and visual-based GUIs?** 
    - This may be helpful if we find that there are groups of users that prefer one interface over the other. While this is partially implemented in our low-fidelity prototype, it is partially encompassed by the goals above.

4. **Do users see themselves continuing to use this app over time/once the novelty wears off?**
    - This is important for the long-term sustainability of the app. However, within the scope of CPSC 444, we may not be able to test this goal effectively. This is something that would need to be tested over a longer period of time, especially because individual users may only use the app every so often.

5. **Do users prefer a more playful/juvenile or serious design?**
    - This is a low priority goal to explore different design and theme options. In particular, we want to see if users will enjoy a funny and playful design, or if they might find it inappropriate for the context.
