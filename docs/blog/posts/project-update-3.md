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

draft: false

slug: project-update-3

---

# CPSC 444 L2B FacilityFinder - Blog Update #3

This blog post will include a revision to the task examples, information about our low-fidelity prototype and cognitive walkthrough, and more thoughts on the overall goals of our experiment. 

<!-- more -->

## 3a. Further Updated Task Examples

!!! quote "Original Task Examples (from blog update #2)"

    Task Example 1: Jeffrey
    
    Jeffrey is a biomedical engineering and experimental medicine graduate student at UBC. They are non-binary and thus feel more comfortable in gender neutral washrooms. They know of 2 bathrooms on campus that are gender neutral: one in their department’s building, and another in the Life building. On occasion, they will need to go to the washroom while exploring a new area of campus. During these times, Jeffrey typically opts for returning to one of their “safe” bathroom spots as they are unfamiliar with which surrounding buildings have gender neutral washrooms, which buildings have restricted access, and where specifically the bathrooms are located within each building. Depending on their current location on campus, they could be very far from the two gender neutral washrooms they know of. They would like to be able to easily and quickly find reliable information on what gender-neutral washrooms are nearby. 
    
    
    Task Example 2: Karen
    
    Karen is a parent taking photos of her son by the UBC fountain before his graduation ceremony. This is her first time on campus, so she is unfamiliar with the facilities. The ceremony is starting soon, so she wants to find a washroom nearby that she can access quickly without much walking since she is wearing uncomfortable shoes. Since it is a later in the day, she is not sure which buildings are open to the public and which ones need keycard access, such as those that are locked after a certain time. It would take some time to check each building for access and facilities, and she is not sure which one will be easiest to access for her. She can ask her son for directions, and he is able to direct her towards a building, but she does not know where to go after entering the building. She looks around for signs but finds none. Instead, she looks around for a floor map and finds an evacuation map that she uses to locate the washroom. 
    
    
    Task Example 3: Marie
    
    Marie is a new teaching staff member at UBC and requires a wheelchair to move across campus. She has not had an orientation of the buildings she is teaching in and is not familiar with where facilities are located. She needs to find a washroom between her classes that is wheelchair accessible. She also wants to find a washroom that is close to her next class but worries about washroom availability with many students also using this time to use the restroom. While on her way to her next class, she happens to find a suitable wheelchair accessible washroom in a quiet area. She has another wheelchair user friend who often has similar difficulty in finding washrooms, so she wants to share information about this washroom with her friend so they can also access it in the future.

<br>



### Revised Task Examples

Two of our task examples remain unchanged, but the second task example called "Karen" has been updated slightly.

!!! info ""

    **Revised Task Example 2: Karen**

    Karen is a parent taking photos of her son at the UBC fountain prior to his wedding ceremony. This is her first time on campus, so she is unfamiliar with the facilities. As this is a private event, there are no UBC staff members that can assist. The ceremony is starting soon, so she wants to find a washroom nearby that she can access quickly without much walking since she is wearing uncomfortable shoes. Since it is a later in the day, she is not sure which buildings are open to the public and which ones need keycard access, such as those that are locked after a certain time. It would take some time to check each building for access and facilities, and she is not sure which one will be easiest to access for her. She can ask her son for directions, and he is able to direct her towards a building, but she does not know where to go after entering the building. 

#### **Explanation of Changes**

We changed the context of the task example to be a wedding ceremony instead of a graduation ceremony. As graduation ceremonies typically have staff and volunteers to help guide guests, we wanted to make the task example more generalized by removing this support. Private weddings events and festivities are not likely to have UBC staff members to assist. This change should make the task example more representative of users that are unfamiliar with the campus and need to find a washroom quickly. We also removed the specific steps Karen took to complete the task, so that the task example would remain open to different solutions. 

<br> 

#### **Other Thoughts**

Other than this change, the task examples remain the same. Our task examples went through a significant update in blog update #2, and they continue to be applicable and relevant to the current direction of our designs. We currently do not have any significant updates to our requirements or methodology to justify changing the other task examples.

---

## 3b. Low-Fidelity Prototype Demonstration

PLACEHOLDER TODO: Add low-fidelity prototype demonstration

---

## 3c. Additional Information about Prototype

### **Prototype Justification**

The chosen design of a mobile app should support all of our task examples. An app provides more flexibility and it can be used on the go, making it suitable for those who have limited time to find a washroom (e.g. Marie and Karen) as well as those who have time to explore. Since UBC Vancouver provides both private and public Wi-Fi access, a mobile app can be easily downloaded by anyone on campus. For example, signs could be placed around campus with a QR code to direct the user to the app. 

This design also accounts for individual user preferences for washroom features and amenities and, it takes measures to categorize them for ease of use. Additionally, since a mobile apps have a built-in update mechanism through the app stores, the app can be updated more quickly and easily to include new features or preferences that aren't currently accounted for. This would be more difficult and expensive with a stationary board or custom devices.

<br> 

### **Focus of Prototype**

For this stage, while we considered exploring both breadth and depth of the design, we focused more on the depth of key features. 

**Design Breadth:**

- Wireframes for all key features have been designed.
- However, some less crucial pages such as the profile page were omitted.


**Design Depth:**

- We paid special attention to key aspects such as searching and viewing washroom details. Interactions on these pages are more complete and flow seamlessly between one another. 

One key design decision we made was to add a toggle on the interface for looking at washroom features. This toggle allows users to switch between a more visual interface with icons and images representing the information, and a denser text-based interface. This was done to accommodate different user preferences and to make the app more accessible to a wider range of users. 

Another design decision made was to leverage positive transfer effect and utilize industry standard interactions such as screens sliding into frame from the right after a button is clicked and swiping from left to right to return to the previous page.

---

## 3d. Cognitive Walkthrough Report

### **Cognitive Walkthrough Goals**

During the cognitive walkthrough, we asked participants to complete the following tasks: 

- Assuming you are somewhere on campus, find a nearby washroom as quickly as possible 
- Assuming you are at the washroom, try to add or update information about the washroom 

<br> 

While the user completed the task, we were looking for the following: 

- How long it took for the user to complete the task 
- Whether the user's conceptual model matched the system's conceptual model, which is to say if the effect of the user's actions matched their expectations 
- Whether the information and buttons were visible and easy to find, once the user knew what they were looking for 
- Once an action was completed, could the user recognize that the action was successful and would they have benefited from any additional feedback 

<br> 

### **Cognitive Walkthrough Results**

**Task 1: Find a nearby washroom as quickly as possible**

We found that the user was able to quickly find the washroom using the quick search button, but they had difficulty getting back to the home screen afterwards as they did not expect to have to swipe from left to right. Once the user got to the directions screen, they understood that they had completed the task.

<br> 

**Task 2: Add or update information about the washroom**

For the second task, the user was able to quickly find the button to add information to the washroom. Their conceptual model matched the system's conceptual model, and they were able to recognize that the action was successful. However, they recommended that the confirmation screen should be more distinct, such as by including a large checkmark.

<br> 

**Overall Feedback**

The user noted that while they could add washroom information easily, they may not have done so unless specifically asked to do so as a task. This suggests that we may need to make the process of adding information more streamlined and intuitive.

One suggestion from the participant was to connect the process of finding a washroom to the process of adding information. The app could either detect when the user has arrived at the washroom, or include a button on the navigation screen to confirm that they had arrived at the washroom. When the arrival was confirmed, the app could automatically open up the add/update information screen. This would make the process of adding information more streamlined, and better address our goal of keeping the information in the app up to date.

---

## 3e. Proposed Goals of Experiment

For our experiment, there are a few goals that we would like to focus on. We have ranked these goals by importance and our ability to test them within the scope of CPSC 444. Our two most important goals are as follows.

1. **Do users feel motivated to add/update washroom data?** 
    - This is the most important goal for our experiment. We want to ensure that the app is sustainable and that the information in the app is up to date. As such, we want to investigate whether or not users feel motivated to add and update washroom data. 
    - While this currently exists in a limited form in our low-fidelity prototype, we will need to expand on this for our evaluation. In particular, we want to explore different ways of motivating users to add and update washroom data. 
        - In particular, we are exploring the use of gamification and social incentives, such as a points system, a leaderboard, and achievements.

2. **Do users prefer a visual or text-based interface?** 
    - This is the second most important goal for our experiment. We want to ensure that the app is accessible and useful for a diverse set of users. As such, we want to investigate the best way to convey the information.
    - This is easy to test since it is already partially implemented in our low-fidelity prototype. For our evaluation, we will ask participants to complete tasks using both the visual and text-based interfaces, and then ask them which one they preferred.

<br>

We also considered a few other goals, but we are unlikely to pursue them in our experiment. Those goals are as follows.

3. **Do users value the option to switch between text-based and visual-based GUIs?** 
    - This may be helpful if we find that there are groups of users that prefer one interface over the other. While this is partially implemented in our low-fidelity prototype, it can be covered by the goals above.

4. **Do users see themselves continuing to use this app over time/once the novelty wears off?**
    - This is important for the long-term sustainability of the app. However, within the scope of CPSC 444, we may not be able to test this goal effectively. This is something that would need to be tested over a long period of time, especially because individual users may only use the app every so often.

5. **Do users prefer a more playful and juvenile design, or a more serious design?**
    - This is a low priority goal to explore different design and theme options. In particular, we want to see if users will enjoy a funny and playful design, or if they might find it inappropriate for the context.
