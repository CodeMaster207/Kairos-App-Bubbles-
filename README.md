# [Project Name] by Project Kairos

Team: Woon Jun Haow, Woo Shao En, Tong Hor Yee, Tan Hui Jing 

Problem Statement: Stress & Workload Manager

Video Presentation: [Unlisted YouTube Link] 

Presentation Slides: https://canva.link/3oq6sd543huz1mu 

## 1. Project Overview
## 1.1 The Problem
University students frequently manage multiple academic, extracurricular, and personal responsibilities simultaneously. Common causes of excessive stress include poor time management, procrastination, accepting too many responsibilities, insufficient rest, overlapping deadlines, and difficulty recognising when their workload has exceeded their personal capacity.

The primary stakeholders are university students who need to balance academic performance with personal well-being. Students who frequently procrastinate may find conventional productivity applications overwhelming or tedious, while highly achievement-oriented students may struggle to decline additional responsibilities and may prioritise productivity at the expense of adequate recovery.

Existing applications such as Google Calendar, Microsoft To Do, Forest, Habitica, and Pomofocus address specific aspects of scheduling, task management, focus, or gamification. However, these solutions generally focus on task completion or time management rather than evaluating whether a student's overall workload is realistically manageable. Students may therefore need to combine several applications while still lacking personalised guidance regarding workload and recovery.

### 1.2 The Solution
Project Kairos is a mental-health-first productivity companion designed to help university students manage both their tasks and their workload capacity. It combines task management with workload awareness, behavioural analysis, and a calming aquarium-based interface. Rather than simply encouraging users to complete more tasks, Kairos aims to help users determine what they can realistically handle and make more sustainable decisions about their workload. 

## 2. Ideation & Process

### 2.1 Ideas We Considered

List of ideas that are brainstormed of and ultimately chosen/modified/postponed/deprioritised after a series of discussions: 
<br>
*Note: Ideas are not specifically bounded by the app flow/pages.*

| **Idea** | **Why it was dropped / kept** |
|---|---|
| Aquarium and Digital Companion (Chosen) | Provides a calming and approachable environment that differentiates Kairos from conventional productivity applications. Retaining users through establishing emotional connection. |
| Task Bubbles (Chosen) | Provides a visual representation of tasks and creates a more engaging interaction when completing tasks. |
| Workload Awareness (Chosen) | Directly addresses the core problem by helping users understand whether their workload is manageable. |
| Behaviour-Based AI (Chosen) | Reduces the need for repeated manual input and enables personalised workload recommendations based on user behaviour. |
| Task Planner (Chosen) | Provides the fundamental functionality required to organise and manage tasks. |
| Recovery Activities (Chosen) | Extends task management beyond productivity by encouraging appropriate periods of recovery. |
| Daily Check-in (Modified) | Initially considered as a manual mood and energy check-in. It was modified so that the system can increasingly infer useful information from user behaviour rather than relying heavily on manual input. |
| Workload Dashboard (Modified) | Retained as a supporting feature, but detailed information is separated from the main aquarium interface to prevent the user from feeling overwhelmed. |
| Reward Centre (Chosen) | Provides motivation through a simple reward system, allowing users to earn and use rewards as they complete tasks and recovery activities. |
| Sleep Tracking (Postponed) | Relevant to overall well-being but outside the priority scope of the MVP. |
| Pomodoro Timer (Chosen) | Supports focused work sessions by helping users manage their time while completing tasks without adding unnecessary complexity to the main workflow. |
| Focus Tunnel (Chosen) | Provides a dedicated environment for users to focus on important tasks and reduce distractions when they need to concentrate. |
| Advanced Health Tracking (Postponed) | Potentially useful for future development but introduces additional complexity that is unnecessary for the initial prototype. |

### 2.2 Ideation Boards
#### Mind Map:
![Coggle Preview](images/Coggle%20Preview.png)
The summary of all the features added/dropped: 
https://coggle.it/diagram/ap1XiDNh0bR-kk44/t/university-student-stress-workload-management/BpqtEU1C8kxFcqLi5rXKS82svB98rNucTVGshKfVzHk 
(*Website/App used: Coggle*)

#### Phase 1: Initialisation — Idea Generation

**1st Draft of the Main Page/Dashboard:**
![Main Page (1st draft)](images/Main%20Page%20(1st%20draft).jpeg)
- A simple sketch of what would be the template for the app's main page/dashboard, with today's to-do and user's health statistics eventually be implemented.

**Art Style of the app:**
![Art Style 1 (Bubbles)](images/Art%20Style%201%20(Bubbles).jpeg)

![Art Style 2 (Bubbles)](images/Art%20Style%202%20(Bubbles).jpeg)

- Eventually, the app style pivoted to ocean theme with bubbles and fish after a series of discussions, where each users' task is represented by a bubble and contributed to the size of the stress ball.
    
- _The mechanisms of the stress ball was eventually dropped but the ocean theme remains, which is reflected by the later stages of app development._
    

---

#### Phase 2: Feature Planning — App Sketch

**1st draft of the To-do List:**

![To-do List 1 (1st draft)](images/To-do%20List%201%20(1st%20draft).jpeg)
![To-do List 2 (1st draft)](images/To-do%20List%202%20(1st%20draft).jpeg)
While highly detailed/technical, it did not fit the art language of the app and thereby redesigned. However, some of the features are retained:
- workload bar where it shows users how much workload they have to bear today.
    
- priority tags where users can choose how urgent they need to solve the task.
    
- behavioural AI that will automatically detect whether the user will have high workload day(s) coming up and thereby will suggest rescheduling some of the tasks.
    

**2nd draft of the Main Page/Dashboard:**
![Main Page (2nd draft)](images/Main%20Page%20(2nd%20draft).png)
Many features were added, most notably:
- Fish tank where users can view their fish.
    
- Quizzes where user can self-assess themselves mentally.
    
    - How are they feeling today?
        
    - What is their energy level?
        
    - And how much hour they have slept yesterday?
        
    - _This feature was eventually dropped in favour of lessening the visual burdens, where users can access it in their individual profile page instead._
        
    - _(The question at the bottom section asked how much should the app prompt the user with quizzes.)_
        
- Tasks they have to do today
    
- Their health statistics
    
    - _This feature was eventually changed to only shown when users scroll down, in favour of lessening the visual burden._
        

**1st draft of the Balancing Page:**
![Balancing Page (1st draft)](images/Balancing%20Page%20(1st%20draft).png)
- Shows users a see-saw widget to visualise the proportions of their time spent on work and social activities.
    
- Their workload status (whether it is healthy, warning, or burnt out).
    
- AI-suggested load balancing actions.
    
- Keep All/Must Finish Today button will bring users to a timer where they can set to focus with the most urgent task shown.
    

**2nd draft of the To-do List:**
![To-do List (2nd draft)](images/To-do%20List%20(2nd%20draft).png)

- Overload bar was replaced with the fish tank.
    
- Features are renamed to make the app tone much more friendly and fit the theme better.
    

**2nd draft of the Balancing Page:**
![Balancing Page (2nd draft)](images/Balancing%20Page%20(2nd%20draft).png)

- See-saw was replaced with the fish tank.
    
- Features are renamed to make the app tone much more friendly and fit the theme better.
    

**Pop-up Model of the Overload Warning:**
- Give users mandatory breaks in-between their tasks (the app will then show that their fishes are being fed).
    

---

#### Phase 3: Feature Clarification

**Teammate felt confused when it came to some features:**

- "The overload banner better put under the seesaw (user will not oversee). Rebalance task and check out list -will it change the to do list sequence also? The check out list is something similar with to do list tab?"
    
- "When click on the overload banner, show the focus.... Does it means that if user timetable cannot be adjust or user don't want to adjust, must so it today so we give them the recommended sequence?"
    

**Eventually, some features are given clarification:**

- "The overload banner is a pop up message"
    
- "Maybe can change for the to do list sequence, but in rebalance page, AI will give u suggestion / or some calculation which task u need to done first"
    

**Feedbacks:**

- "Actually this idea is good and related to the fish theme, but just a minor change, I think the add button can put on right side."
    
- "And then oxygen is note for your self only or included in UI, and I don't really get the high oxygen consumption..... Different term, based on what to categorise."
    

**Extra feedbacks:**
![Balancing Page (feedback for 1st draft)](images/Balancing%20Page%20(feedback%20for%201st%20draft).png)

![To-do List (feedback for 2nd draft)](images/To-do%20List%20(feedback%20for%202nd%20draft).png)

![Balancing Page (feedback for 2nd draft)](images/Balancing%20Page%20(feedback%20for%202nd%20draft).png)
---
#### Phase 4: Further Refinement

**3rd draft of the Main Page/Dashboard:**
![Main Page (3rd draft)](images/Main%20Page%20(3rd%20draft).png)
- Focus on adding button features
    
    - **Emotion record chart** where users can see how well they are doing mentally.
        
    - Edit button to key in their mental wellbeing details manually.
        

**1st draft of the Profile page:**
![Profile Page](images/Profile%20Page.png)
Users can view their:

- current pet fish and its costume.
    
- modify their pet fish (which fish to appear in the main page/dashboard).
    
- edit their profile.
    
- browse through their achievements (in the form of fish costumes collected).
    
- adjust their preferences and use other accessibility settings.
    

---

#### Phase 5: 1st Mentor's Feedback
After receiving some feedbacks and comments from our 1st mentor (Teh Ming En), the UI is further refined. 
**4th draft of the Main Page/Dashboard:**
![Main Page (4th draft)](images/Main%20Page%20(4th%20draft).jpg)

To reduce the visual burden, users will now on only see:  
- their favourite fish tank and fish at the top section
- with their today's to-do tasks at the bottom section
- their health statistics after manually scrolling down

**3th draft of the To-do List:**<br>
Additional refinements to the To-do List's interface: 
![Balancing Page (3rd draft)](images/Balancing%20Page%20(3rd%20draft).jpg)

**3th draft of the Balancing Page:**<br>
Additional refinements to the Balancing Page's interface: 
![To-do List (3rd draft)](images/To-do%20List%20(3rd%20draft).jpg)

**The latest drafts of the UI are then used to finalise the designs in Figma.** 
---

#### Phase 6: Final Design Direction

**Visual Direction:**

- Ocean theme
    
- Aquarium
    
- Fish
    
- Bubbles
    

**Core Functionality:**

- Task management
    
- Workload awareness
    
- Priority management
    
- Behaviour-based AI
    
- Overload warnings
    
- Recovery activities
    

**Design Principles:**

- Reduce visual burden
    
- Use friendlier terminology
    
- Maintain a consistent visual language
    
- Reduce unnecessary user input
    
- Focus on the core workload-management experience

### Phase 7: Second Mentor Feedback
After receiving some feedbacks and comments from our 2nd mentor (Teng Wei Herr), the UI is further refined directly in the Figma Website/App. 

---

### Phase 8: Final Demo Design
After both the mentor sessions and discussions, the final design is profuced for each of the app page




### 2.3 Mentor Consultation
| **Date**         | **Mentor**  | **Feedback Received**                                                                                                                  | **What Was Changed**                                                                                                                       |
| ---------------- | ----------- | -------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| 6 September 2026 | Teh Ming En | Integrate AI more meaningfully into the system and establish it as a stronger selling point.                                           | Behaviour-based AI was incorporated as a core component for analysing user behaviour and generating personalised workload recommendations. |
| 6 September 2026 | Teh Ming En | Ensure that Figma can effectively communicate the proposed UI and begin developing the main functionality.                             | The aquarium and task-bubble interaction were prioritised as the main prototype experience.                                                |
| 6 September 2026 | Teh Ming En | Focus on the main objective and postpone features such as Pomodoro and Focus Tunnel.                                                   | Pomodoro and Focus Tunnel were deprioritised to maintain a focused MVP centred on workload management.                                     |
| 6 September 2026 | Teh Ming En | Sleep tracking does not need to be implemented at the current stage.                                                                   | Sleep tracking was moved to the future development scope.                                                                                  |
| 6 September 2026 | Teh Ming En | The reward store does not need to be implemented at the current stage.                                                                 | The reward store was postponed to a future development phase.                                                                              |
| 6 September 2026 | Teh Ming En | Avoid requiring excessive user input and consider calculating information from user behaviour.                                         | Behaviour-based analysis was prioritised to reduce manual input and support personalised recommendations.                                  |
| 6 September 2026 | Teh Ming En | Avoid making the user interface unnecessarily complicated.                                                                             | The main interface was simplified and detailed information was moved to secondary pages.                                                   |
| 6 September 2026 | Teh Ming En | The main page should primarily allow users to view the aquarium and bubbles, while complicated information should be placed elsewhere. | The aquarium became the primary visual element of the main page, with detailed workload information separated into dedicated sections.     |
| 6 September 2026 | Teh Ming En | Develop a more engaging explanation for why users would need the application.                                                          | The aquarium was positioned as a calming entry point, while workload intelligence provides the primary functional value.                   |
| 6 September 2026 | Teh Ming En | Ensure that the proposed features are feasible and postpone technically difficult features where necessary.                            | The MVP scope was narrowed, with non-essential and complex features moved to future development.                                           |

Main Takeaway: 
- 6th Sep (Teh Ming En): Cutting visual burden as much as possible, prioritising features that are essential to the user experiences, putting delivering a usable MVP as the main focus before executing on ambitious plans to expand on other features.
<br><br>

| Date | Mentor | Feedback / Suggestion | Action Taken / Proposed Improvement |
|---|---|---|---|
| 12 Sep 2026 | Teng Wei Herr | Allow users to cancel or skip a task during rebalancing if they do not want to complete it that day. | Add a **Cancel Task** option during rebalancing. |
| 12 Sep 2026 | Teng Wei Herr | Combine today's mood log with the daily streak. | Combine both functions for a simpler user experience. |
| 12 Sep 2026 | Teng Wei Herr | Make the aquarium's stress state more obvious, such as changing the water to red. | Enhance the aquarium's visual feedback to clearly indicate high stress. |
| 12 Sep 2026 | Teng Wei Herr | Show the potential stress impact when adding a task. | Display the task's impact on the user's stress/workload state and show a visual reaction from the fish. |
| 12 Sep 2026 | Teng Wei Herr | Tasks that must be completed today should appear at the top of the main page. | Prioritise **Must Do Today** tasks on the main page and simplify other information. |
| 12 Sep 2026 | Teng Wei Herr | Keep the report concise and focus on the mind flow. | Trim unnecessary content and focus on how the team arrived at the current solution. |
| 12 Sep 2026 | Teng Wei Herr | Focus on core features in the video rather than additional features such as daily streak. | Clearly distinguish **core features** from **additional features** and prioritise the core features in the video. |

<br>
Main Takeaway: 

- 12th Sep (Teng Wei Herr): The features are overall well-defined, with many of them directly addressing the issues identified in the problem statement. However, some features can be given further refinement to provide clearer and more intuitive visual cues to users.

## 3. Design & Prototype

UI Prototype: [ Public Link ]


## 4. What Makes It Different

Project Kairos differentiates itself by combining productivity management with workload awareness and a calming companion-oriented experience.

### Aquarium as a Productivity Companion

Rather than presenting users with a conventional task list immediately, Kairos uses an aquarium as the primary interface. This creates a calmer and more approachable environment for interacting with tasks.

### Task Bubbles

Tasks are represented as bubbles, providing a visual representation of workload. Completing a task can be represented through an interactive bubble, making task completion more engaging than a conventional checklist.

### Workload Capacity Awareness

Kairos does not focus solely on whether tasks are completed. It evaluates the user's overall workload and considers whether the amount of work is realistically manageable.

### Behaviour-Based AI

The system aims to analyse patterns such as task completion, delays, task duration, and workload behaviour. These patterns can be used to provide personalised recommendations without requiring users to manually configure every aspect of their schedule.

### Mental-Health-First Productivity

The primary objective is sustainable productivity rather than maximising task completion. Kairos considers recovery and workload capacity as part of productivity management.

### Comparison with Existing Apps

| **Aspect**                            | **Conventional Task Manager** | **Gamified Productivity Application** | **Project Kairos** |
| ------------------------------------- | ----------------------------- | ------------------------------------- | ------------------ |
| Task management                       | Yes                           | Yes                                   | Yes                |
| Gamification                          | Limited                       | Strong                                | Integrated         |
| Digital companion                     | No                            | Sometimes                             | Aquarium-based     |
| Workload awareness                    | Limited                       | Limited                               | Core function      |
| Behaviour-based recommendations       | Limited                       | Limited                               | Core function      |
| Mental-health-first approach          | Limited                       | Limited                               | Central principle  |
| Recovery consideration                | Limited                       | Limited                               | Integrated         |
| Personalised workload recommendations | Limited                       | Limited                               | Yes                |

## 5. Technical Architecture & Feasibility

### 5.1 Tech stack

| **Component**     | **Technology**               | **Reason / Constraint**                                                                                                                                                       |
| ----------------- | ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Frontend          | React / Next.js              | Suitable for building an interactive web interface and supports component-based development. The main constraint is the team's familiarity with JavaScript-based development. |
| Backend           | Flask / FastAPI              | Python-based frameworks are suitable for implementing the workload logic and integrating AI services.                                                                         |
| Database          | PostgreSQL / Supabase        | Provides structured storage for users, tasks, workload information, and behavioural data. Supabase is considered as an option rather than a mandatory dependency.             |
| Authentication    | JWT / Managed Authentication | Provides a practical mechanism for user authentication while keeping the backend architecture modular.                                                                        |
| AI Service        | External AI API              | Used to support behaviour-based analysis and personalised recommendations rather than functioning as a standalone chatbot.                                                    |
| API Communication | REST API                     | Provides a straightforward method for communication between the frontend, backend, and supporting services.                                                                   |
| Hosting           | Cloud-based hosting          | Allows the prototype to be demonstrated remotely without requiring local deployment.                                                                                          |
The architecture is intentionally modular so that individual technologies can be replaced if development constraints arise.


### 5.2 System architecture diagram

![System Architecture Diagram](images/System%20Architecture%20Diagram.png)

# [Project Name] by Project Kairos

Team: Woon Jun Haow, Woo Shao En, Tong Hor Yee, Tan Hui Jing 

Problem Statement: Stress & Workload Manager

Video Presentation: [Unlisted YouTube Link] 

Presentation Slides: https://canva.link/3oq6sd543huz1mu 

## 1. Project Overview
## 1.1 The Problem
University students frequently manage multiple academic, extracurricular, and personal responsibilities simultaneously. Common causes of excessive stress include poor time management, procrastination, accepting too many responsibilities, insufficient rest, overlapping deadlines, and difficulty recognising when their workload has exceeded their personal capacity.

The primary stakeholders are university students who need to balance academic performance with personal well-being. Students who frequently procrastinate may find conventional productivity applications overwhelming or tedious, while highly achievement-oriented students may struggle to decline additional responsibilities and may prioritise productivity at the expense of adequate recovery.

Existing applications such as Google Calendar, Microsoft To Do, Forest, Habitica, and Pomofocus address specific aspects of scheduling, task management, focus, or gamification. However, these solutions generally focus on task completion or time management rather than evaluating whether a student's overall workload is realistically manageable. Students may therefore need to combine several applications while still lacking personalised guidance regarding workload and recovery.

### 1.2 The Solution
Project Kairos is a mental-health-first productivity companion designed to help university students manage both their tasks and their workload capacity. It combines task management with workload awareness, behavioural analysis, and a calming aquarium-based interface. Rather than simply encouraging users to complete more tasks, Kairos aims to help users determine what they can realistically handle and make more sustainable decisions about their workload. 

## 2. Ideation & Process

### 2.1 Ideas We Considered

List of ideas that are brainstormed of and ultimately chosen/modified/postponed/deprioritised after a series of discussions: 
<br>
*Note: Ideas are not specifically bounded by the app flow/pages.*

| **Idea** | **Why it was dropped / kept** |
|---|---|
| Aquarium and Digital Companion (Chosen) | Provides a calming and approachable environment that differentiates Kairos from conventional productivity applications. Retaining users through establishing emotional connection. |
| Task Bubbles (Chosen) | Provides a visual representation of tasks and creates a more engaging interaction when completing tasks. |
| Workload Awareness (Chosen) | Directly addresses the core problem by helping users understand whether their workload is manageable. |
| Behaviour-Based AI (Chosen) | Reduces the need for repeated manual input and enables personalised workload recommendations based on user behaviour. |
| Task Planner (Chosen) | Provides the fundamental functionality required to organise and manage tasks. |
| Recovery Activities (Chosen) | Extends task management beyond productivity by encouraging appropriate periods of recovery. |
| Daily Check-in (Modified) | Initially considered as a manual mood and energy check-in. It was modified so that the system can increasingly infer useful information from user behaviour rather than relying heavily on manual input. |
| Workload Dashboard (Modified) | Retained as a supporting feature, but detailed information is separated from the main aquarium interface to prevent the user from feeling overwhelmed. |
| Reward Centre (Chosen) | Provides motivation through a simple reward system, allowing users to earn and use rewards as they complete tasks and recovery activities. |
| Sleep Tracking (Postponed) | Relevant to overall well-being but outside the priority scope of the MVP. |
| Pomodoro Timer (Chosen) | Supports focused work sessions by helping users manage their time while completing tasks without adding unnecessary complexity to the main workflow. |
| Focus Tunnel (Chosen) | Provides a dedicated environment for users to focus on important tasks and reduce distractions when they need to concentrate. |
| Advanced Health Tracking (Postponed) | Potentially useful for future development but introduces additional complexity that is unnecessary for the initial prototype. |

### 2.2 Ideation Boards
#### Mind Map:
![Coggle Preview](images/Coggle%20Preview.png)
The summary of all the features added/dropped: 
https://coggle.it/diagram/ap1XiDNh0bR-kk44/t/university-student-stress-workload-management/BpqtEU1C8kxFcqLi5rXKS82svB98rNucTVGshKfVzHk 
(*Website/App used: Coggle*)

#### Phase 1: Initialisation — Idea Generation

**1st Draft of the Main Page/Dashboard:**
![Main Page (1st draft)](images/Main%20Page%20(1st%20draft).jpeg)
- A simple sketch of what would be the template for the app's main page/dashboard, with today's to-do and user's health statistics eventually be implemented.

**Art Style of the app:**
![Art Style 1 (Bubbles)](images/Art%20Style%201%20(Bubbles).jpeg)

![Art Style 2 (Bubbles)](images/Art%20Style%202%20(Bubbles).jpeg)

- Eventually, the app style pivoted to ocean theme with bubbles and fish after a series of discussions, where each users' task is represented by a bubble and contributed to the size of the stress ball.
    
- _The mechanisms of the stress ball was eventually dropped but the ocean theme remains, which is reflected by the later stages of app development._
    

---

#### Phase 2: Feature Planning — App Sketch

**1st draft of the To-do List:**

![To-do List 1 (1st draft)](images/To-do%20List%201%20(1st%20draft).jpeg)
![To-do List 2 (1st draft)](images/To-do%20List%202%20(1st%20draft).jpeg)
While highly detailed/technical, it did not fit the art language of the app and thereby redesigned. However, some of the features are retained:
- workload bar where it shows users how much workload they have to bear today.
    
- priority tags where users can choose how urgent they need to solve the task.
    
- behavioural AI that will automatically detect whether the user will have high workload day(s) coming up and thereby will suggest rescheduling some of the tasks.
    

**2nd draft of the Main Page/Dashboard:**
![Main Page (2nd draft)](images/Main%20Page%20(2nd%20draft).png)
Many features were added, most notably:
- Fish tank where users can view their fish.
    
- Quizzes where user can self-assess themselves mentally.
    
    - How are they feeling today?
        
    - What is their energy level?
        
    - And how much hour they have slept yesterday?
        
    - _This feature was eventually dropped in favour of lessening the visual burdens, where users can access it in their individual profile page instead._
        
    - _(The question at the bottom section asked how much should the app prompt the user with quizzes.)_
        
- Tasks they have to do today
    
- Their health statistics
    
    - _This feature was eventually changed to only shown when users scroll down, in favour of lessening the visual burden._
        

**1st draft of the Balancing Page:**
![Balancing Page (1st draft)](images/Balancing%20Page%20(1st%20draft).png)
- Shows users a see-saw widget to visualise the proportions of their time spent on work and social activities.
    
- Their workload status (whether it is healthy, warning, or burnt out).
    
- AI-suggested load balancing actions.
    
- Keep All/Must Finish Today button will bring users to a timer where they can set to focus with the most urgent task shown.
    

**2nd draft of the To-do List:**
![To-do List (2nd draft)](images/To-do%20List%20(2nd%20draft).png)

- Overload bar was replaced with the fish tank.
    
- Features are renamed to make the app tone much more friendly and fit the theme better.
    

**2nd draft of the Balancing Page:**
![Balancing Page (2nd draft)](images/Balancing%20Page%20(2nd%20draft).png)

- See-saw was replaced with the fish tank.
    
- Features are renamed to make the app tone much more friendly and fit the theme better.
    

**Pop-up Model of the Overload Warning:**
- Give users mandatory breaks in-between their tasks (the app will then show that their fishes are being fed).
    

---

#### Phase 3: Feature Clarification

**Teammate felt confused when it came to some features:**

- "The overload banner better put under the seesaw (user will not oversee). Rebalance task and check out list -will it change the to do list sequence also? The check out list is something similar with to do list tab?"
    
- "When click on the overload banner, show the focus.... Does it means that if user timetable cannot be adjust or user don't want to adjust, must so it today so we give them the recommended sequence?"
    

**Eventually, some features are given clarification:**

- "The overload banner is a pop up message"
    
- "Maybe can change for the to do list sequence, but in rebalance page, AI will give u suggestion / or some calculation which task u need to done first"
    

**Feedbacks:**

- "Actually this idea is good and related to the fish theme, but just a minor change, I think the add button can put on right side."
    
- "And then oxygen is note for your self only or included in UI, and I don't really get the high oxygen consumption..... Different term, based on what to categorise."
    

**Extra feedbacks:**
![Balancing Page (feedback for 1st draft)](images/Balancing%20Page%20(feedback%20for%201st%20draft).png)

![To-do List (feedback for 2nd draft)](images/To-do%20List%20(feedback%20for%202nd%20draft).png)

![Balancing Page (feedback for 2nd draft)](images/Balancing%20Page%20(feedback%20for%202nd%20draft).png)

---

#### Phase 4: Further Refinement

**3rd draft of the Main Page/Dashboard:**
![Main Page (3rd draft)](images/Main%20Page%20(3rd%20draft).png)
- Focus on adding button features
    
    - **Emotion record chart** where users can see how well they are doing mentally.
        
    - Edit button to key in their mental wellbeing details manually.
        

**1st draft of the Profile page:**
![Profile Page](images/Profile%20Page.png)
Users can view their:

- current pet fish and its costume.
    
- modify their pet fish (which fish to appear in the main page/dashboard).
    
- edit their profile.
    
- browse through their achievements (in the form of fish costumes collected).
    
- adjust their preferences and use other accessibility settings.
    

---

#### Phase 5: 1st Mentor's Feedback
After receiving some feedbacks and comments from our 1st mentor (Teh Ming En), the UI is further refined. 
**4th draft of the Main Page/Dashboard:**
![Main Page (4th draft)](images/Main%20Page%20(4th%20draft).jpg)

To reduce the visual burden, users will now on only see:  
- their favourite fish tank and fish at the top section
- with their today's to-do tasks at the bottom section
- their health statistics after manually scrolling down

**3th draft of the To-do List:**<br>
Additional refinements to the To-do List's interface: 
![Balancing Page (3rd draft)](images/Balancing%20Page%20(3rd%20draft).jpg)

**3th draft of the Balancing Page:**<br>
Additional refinements to the Balancing Page's interface: 
![To-do List (3rd draft)](images/To-do%20List%20(3rd%20draft).jpg)

**The latest drafts of the UI are then used to finalise the designs in Figma.** 
---

#### Phase 6: Final Design Direction

**Visual Direction:**

- Ocean theme
    
- Aquarium
    
- Fish
    
- Bubbles
    

**Core Functionality:**

- Task management
    
- Workload awareness
    
- Priority management
    
- Behaviour-based AI
    
- Overload warnings
    
- Recovery activities
    

**Design Principles:**

- Reduce visual burden
    
- Use friendlier terminology
    
- Maintain a consistent visual language
    
- Reduce unnecessary user input
    
- Focus on the core workload-management experience

#### Phase 7: Second Mentor Feedback
After receiving some feedbacks and comments from our 2nd mentor (Teng Wei Herr), the UI is further refined directly in the Figma Website/App. 

---

#### Phase 8: Final Demo Design
After both the mentor sessions and discussions, the final design is profuced for each of the app page




### 2.3 Mentor Consultation
| **Date**         | **Mentor**  | **Feedback Received**                                                                                                                  | **What Was Changed**                                                                                                                       |
| ---------------- | ----------- | -------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| 6 September 2026 | Teh Ming En | Integrate AI more meaningfully into the system and establish it as a stronger selling point.                                           | Behaviour-based AI was incorporated as a core component for analysing user behaviour and generating personalised workload recommendations. |
| 6 September 2026 | Teh Ming En | Ensure that Figma can effectively communicate the proposed UI and begin developing the main functionality.                             | The aquarium and task-bubble interaction were prioritised as the main prototype experience.                                                |
| 6 September 2026 | Teh Ming En | Focus on the main objective and postpone features such as Pomodoro and Focus Tunnel.                                                   | Pomodoro and Focus Tunnel were deprioritised to maintain a focused MVP centred on workload management.                                     |
| 6 September 2026 | Teh Ming En | Sleep tracking does not need to be implemented at the current stage.                                                                   | Sleep tracking was moved to the future development scope.                                                                                  |
| 6 September 2026 | Teh Ming En | The reward store does not need to be implemented at the current stage.                                                                 | The reward store was postponed to a future development phase.                                                                              |
| 6 September 2026 | Teh Ming En | Avoid requiring excessive user input and consider calculating information from user behaviour.                                         | Behaviour-based analysis was prioritised to reduce manual input and support personalised recommendations.                                  |
| 6 September 2026 | Teh Ming En | Avoid making the user interface unnecessarily complicated.                                                                             | The main interface was simplified and detailed information was moved to secondary pages.                                                   |
| 6 September 2026 | Teh Ming En | The main page should primarily allow users to view the aquarium and bubbles, while complicated information should be placed elsewhere. | The aquarium became the primary visual element of the main page, with detailed workload information separated into dedicated sections.     |
| 6 September 2026 | Teh Ming En | Develop a more engaging explanation for why users would need the application.                                                          | The aquarium was positioned as a calming entry point, while workload intelligence provides the primary functional value.                   |
| 6 September 2026 | Teh Ming En | Ensure that the proposed features are feasible and postpone technically difficult features where necessary.                            | The MVP scope was narrowed, with non-essential and complex features moved to future development.                                           |

Main Takeaway: 
- 6th Sep (Teh Ming En): Cutting visual burden as much as possible, prioritising features that are essential to the user experiences, putting delivering a usable MVP as the main focus before executing on ambitious plans to expand on other features.
<br><br>

| Date | Mentor | Feedback / Suggestion | Action Taken / Proposed Improvement |
|---|---|---|---|
| 12 Sep 2026 | Teng Wei Herr | Allow users to cancel or skip a task during rebalancing if they do not want to complete it that day. | Add a **Cancel Task** option during rebalancing. |
| 12 Sep 2026 | Teng Wei Herr | Combine today's mood log with the daily streak. | Combine both functions for a simpler user experience. |
| 12 Sep 2026 | Teng Wei Herr | Make the aquarium's stress state more obvious, such as changing the water to red. | Enhance the aquarium's visual feedback to clearly indicate high stress. |
| 12 Sep 2026 | Teng Wei Herr | Show the potential stress impact when adding a task. | Display the task's impact on the user's stress/workload state and show a visual reaction from the fish. |
| 12 Sep 2026 | Teng Wei Herr | Tasks that must be completed today should appear at the top of the main page. | Prioritise **Must Do Today** tasks on the main page and simplify other information. |
| 12 Sep 2026 | Teng Wei Herr | Keep the report concise and focus on the mind flow. | Trim unnecessary content and focus on how the team arrived at the current solution. |
| 12 Sep 2026 | Teng Wei Herr | Focus on core features in the video rather than additional features such as daily streak. | Clearly distinguish **core features** from **additional features** and prioritise the core features in the video. |

<br>
Main Takeaway: 

- 12th Sep (Teng Wei Herr): The features are overall well-defined, with many of them directly addressing the issues identified in the problem statement. However, some features can be given further refinement to provide clearer and more intuitive visual cues to users.

## 3. Design & Prototype

UI Prototype: [ Public Link ]


## 4. What Makes It Different

Project Kairos differentiates itself by combining productivity management with workload awareness and a calming companion-oriented experience.

### Aquarium as a Productivity Companion

Rather than presenting users with a conventional task list immediately, Kairos uses an aquarium as the primary interface. This creates a calmer and more approachable environment for interacting with tasks.

### Task Bubbles

Tasks are represented as bubbles, providing a visual representation of workload. Completing a task can be represented through an interactive bubble, making task completion more engaging than a conventional checklist.

### Workload Capacity Awareness

Kairos does not focus solely on whether tasks are completed. It evaluates the user's overall workload and considers whether the amount of work is realistically manageable.

### Behaviour-Based AI

The system aims to analyse patterns such as task completion, delays, task duration, and workload behaviour. These patterns can be used to provide personalised recommendations without requiring users to manually configure every aspect of their schedule.

### Mental-Health-First Productivity

The primary objective is sustainable productivity rather than maximising task completion. Kairos considers recovery and workload capacity as part of productivity management.

### Comparison with Existing Apps

| **Aspect**                            | **Conventional Task Manager** | **Gamified Productivity Application** | **Project Kairos** |
| ------------------------------------- | ----------------------------- | ------------------------------------- | ------------------ |
| Task management                       | Yes                           | Yes                                   | Yes                |
| Gamification                          | Limited                       | Strong                                | Integrated         |
| Digital companion                     | No                            | Sometimes                             | Aquarium-based     |
| Workload awareness                    | Limited                       | Limited                               | Core function      |
| Behaviour-based recommendations       | Limited                       | Limited                               | Core function      |
| Mental-health-first approach          | Limited                       | Limited                               | Central principle  |
| Recovery consideration                | Limited                       | Limited                               | Integrated         |
| Personalised workload recommendations | Limited                       | Limited                               | Yes                |

## 5. Technical Architecture & Feasibility

### 5.1 Tech stack

| **Component**     | **Technology**               | **Reason / Constraint**                                                                                                                                                       |
| ----------------- | ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Frontend          | React / Next.js              | Suitable for building an interactive web interface and supports component-based development. The main constraint is the team's familiarity with JavaScript-based development. |
| Backend           | Flask / FastAPI              | Python-based frameworks are suitable for implementing the workload logic and integrating AI services.                                                                         |
| Database          | PostgreSQL / Supabase        | Provides structured storage for users, tasks, workload information, and behavioural data. Supabase is considered as an option rather than a mandatory dependency.             |
| Authentication    | JWT / Managed Authentication | Provides a practical mechanism for user authentication while keeping the backend architecture modular.                                                                        |
| AI Service        | External AI API              | Used to support behaviour-based analysis and personalised recommendations rather than functioning as a standalone chatbot.                                                    |
| API Communication | REST API                     | Provides a straightforward method for communication between the frontend, backend, and supporting services.                                                                   |
| Hosting           | Cloud-based hosting          | Allows the prototype to be demonstrated remotely without requiring local deployment.                                                                                          |
The architecture is intentionally modular so that individual technologies can be replaced if development constraints arise.


### 5.2 System architecture diagram

![System Architecture Diagram](images/System%20Architecture%20Diagram.png)

### 5.3 Build plan & scope

The building phase will prioritise the core functionality required to demonstrate the central concept.

1. Implement task creation, editing, deletion, and completion.
2. Implement task priorities and deadlines.
3. Develop the aquarium-based main interface.
4. Implement task bubbles and visual workload indicators.
5. Develop basic workload scoring and capacity analysis.
6. Implement workload visualisation and stress-state feedback.
7. Implement task rebalancing, including AI-suggested workload adjustments and task cancellation.
8. Integrate behaviour-based recommendations.
9. Implement basic recovery activities and stress management features.
10. Connect the frontend, backend, database, and AI service.
11. Test and refine the primary user flow.

### 5.4: (Extra) Features Outside the Initial MVP

The following features will be considered additional features and may be postponed if they affect the feasibility of the core system:

- Sleep tracking
- Advanced fish and aquarium customisation
- Advanced health tracking
- Complex external integrations
- Advanced AI modelling