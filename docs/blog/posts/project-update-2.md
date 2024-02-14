---
authors:
  - felicia
  - kae
  - justin
  - rafi

categories:
 - Project Update
 - CPSC 444

date: 2024-02-13

draft: false

slug: project-update-2

---

# Project Update 2

This blog post will include some revisions to the task examples, based on our notes after running a field study. We will also discuss the progress we have made on the project so far, and our recommendations for the next steps. This post will also include the major requirements and user groups that we intend to focus on. Finally, we will propose a few design ideas and alternatives for the project. 

<!-- more -->

## 2b. Task Examples

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

After conducting a field study, we have revised the task examples to better reflect the needs of our users.



!!! info ""

    **Revised Task Example 1: Jeffrey**

    Jeffrey is a biomedical engineering and experimental medicine graduate student at UBC. They are non-binary and thus feel more comfortable in gender neutral washrooms. They know of 2 bathrooms on campus that are gender neutral: one in their department’s building, and another in the Life building. On occasion, they will need to go to the washroom while exploring a new area of campus. During these times, Jeffrey typically opts for returning to one of their “safe” bathroom spots as they are unfamiliar with which surrounding buildings have gender neutral washrooms, which buildings have restricted access, and where specifically the bathrooms are located within each building. Depending on their current location on campus, they could be very far from the two gender neutral washrooms they know of. They would like to be able to easily and quickly find reliable information on what gender-neutral washrooms are nearby.  

!!! info ""

    **Revised Task Example 2: Karen**

    Karen is a parent taking photos of her son by the UBC fountain before his graduation ceremony. This is her first time on campus, so she is unfamiliar with the facilities. The ceremony is starting soon, so she wants to find a washroom nearby that she can access quickly without much walking since she is wearing uncomfortable shoes. Since it is a later in the day, she is not sure which buildings are open to the public and which ones need keycard access, such as those that are locked after a certain time. It would take some time to check each building for access and facilities, and she is not sure which one will be easiest to access for her. She can ask her son for directions, and he is able to direct her towards a building, but she does not know where to go after entering the building. She looks around for signs but finds none. Instead, she looks around for a floor map and finds an evacuation map that she uses to locate the washroom.  


!!! info ""

    **Revised Task Example 3: Marie**

    PLACEHOLDER TEXT

<br>

**Justification:**

After completing the field study, we reevaluated our task examples. In particular, we added further detail to the Karen task example and reoriented our Jeffrey task example towards a new direction.  

For the Karen task example, our original example ended when Karen located a suitable building. Following our field study results, we found that locating washrooms after entering buildings was just as important as finding a suitable building. As such, we adjusted our Karen task example to add further detail on what happens after she enters a building, and the strategies she might employ to locate a washroom.  

Our Jeffrey task example originally focused on a parent requiring changing tables to care for their child. During our field study however, we had difficulty acquiring data from parents with young children. While changing tables are an important amenity that can be incorporated as a filter option in our future prototypes, for now will focus on the data we do have access to. We decided to reorient our task example to focus on an individual seeking gender-neutral washrooms as this was an important topic that we came across in our field studies. We adjusted the task example to replace known washrooms with changing tables to known gender-neutral washrooms, a situation we saw in one of our field study interviews.  








<br><br>

## 2a. Next Steps


PLACEHOLDER TEXT


<br><br>

## 2c. Prioritized List of Requirements

PLACEHOLDER TEXT



<br><br>

## 2d. Design Alternatives

After completing our field study, we have identified a few design alternatives that we would like to explore further. 

<br>

!!! info "You can click on the design alternative images to view them in full size"




**Design 1: Mobile Application focussed on filtering**

Description: 

  - This design prioritizes the use of filters to help users find the information that applies to them. By placing the filters on the home page, users can quickly filter the washroom information across the application.
  - The user can see live updates of the filtering at the top of the screen, where there are 'story bubbles' with the nearest washrooms that meet the filter criteria. Tapping on a story bubble will bring up information for that washroom.
  - There are also buttons on most pages to access the map. The map will show the user's location and the location of the washrooms that meet the filter criteria.


<figure markdown="span"  >
![App Design Home Page](../../assets/img/blog/posts/project-update-2/cpsc444-MII-B2_1.png){ align=left width=210px } 

![App Design Story Page](../../assets/img/blog/posts/project-update-2/cpsc444-MII-B2_2.png){ align=left width=210px } 

![App Design Map Page](../../assets/img/blog/posts/project-update-2/cpsc444-MII-B2_3.png){ align=left width=210px }

<figcaption>Potential design for the mobile application.</figcaption>
</figure>


PROS:

  - The filtering system is easy to use and understand.
  - The live updates of the filtering results are helpful for users who are in a hurry.
  - The map is easily accessible from most pages, making it easy for users to find their way to the washrooms.

CONS:

  - The filtering system may not be as helpful for users who are not sure what they are looking for.
  - The live updates may be distracting for some users.
  - The map may not be as helpful for users who are not familiar with the campus layout.

<br>

**Design 2: Interactive Display Board**

Description:

  - This design is a large interactive display board that is placed in a central location on campus. The board will show a map of the campus with the locations of the washrooms marked. Users can tap on a particular washroom on the board to find more information about the washrooms.


<figure markdown="span"  >

![Design of Interactive Display Board](../../assets/img/blog/posts/project-update-2/cpsc444-MII-B2_4.png){ align=center width=500px } 

<figcaption>Potential design for the interactive display board.</figcaption>
</figure>

PROS:

  - 

CONS:

-  

<br>

**Design 3: Wearable Device App**

Description:

-  


<figure markdown="span"  >

![Design of the Wearable Device App](../../assets/img/blog/posts/project-update-2/cpsc444-MII-B2_5.png){ align=center width=500px } 

<figcaption>Potential design for the wearable device app.</figcaption>
</figure>

PROS:

  - 

CONS:

-  

<br>

**Design 4: AR Wayfinding App**

<figure markdown="span"  >

![Design of AR Wayfinding App](../../assets/img/blog/posts/project-update-2/cpsc444-MII-B2_6.png){ align=center width=500px } 

<figcaption>Potential design for the AR wayfinding app.</figcaption>
</figure>

PROS:

  - 

CONS:

-  

<br>



