# Introduction

- Project Management Tools have a history of being disliked across teams of different sizes, backgrounds and fields. 
- Why? Added overheads, increased accountability, lack of structure/understanding to use.
- When a project management tool fails, more often than not, it’s because of a lack of structure of how to use it. 
- But, the tool should be able to understand how its users would use 
- Since this is an internal project management tool, can be designed specifically for use at Marwadi

## Approach and Process

We approached the audit differently than a standard UX audit. Besides just marking out issues and areas for potential issues, we’ve also provided our thoughts on design and structure changes that would make the product experience much better. We broke the process into 2 phases; Discovery and Analysis:

### Phase 1 - Discovery
The discovery phase included:
-   **Understanding Internal Processes and Users**:  
     What are the type of projects that are taken up and that will be managed on this platform? Who are the users, what are their roles and how would they be using this platform? Are there any specific project management processes in place already, that need to be carried forward into the platform? We uncovered answers to this through discussions with Mr. Jeet Marwadi.  
      
    
-   **Understanding decisions taken in the new platform and the old platform**
We did a detailed analysis of the new platform to understand what design decisions were taken, and why they were taken. We also went through the older TASK and Sync tools that were being used to see how users were using them, and to understand design decisions that were taken in those.

-   **Analysing existing project management tools for reference**
We analysed several of the top project management tools like Asana, Trello, TeamWeek, Monday, Good Day, and others to see patterns and processes they’re using, in case any of them could be relevant for Sync’s use.
	
	![Asana](https://raw.githubusercontent.com/chrisdsouza196/Marwadi/master/asana.png =75x50)

### Phase 2 - Analysis and Recommendations
Analysis was done across different types of checks.

While working on the analysis of the tool, we realised we had to take implementation of fixes and suggestions into account as well.

-   **Product Analysis across 2 levels**:  
    Level 1 - Heuristic principles, usability, broken user flows, basic UX issues and content/copy issues .
     
    Level 2 - Analyse Core flows, evaluate if core flows are being achieved successfully, and if the experience is going to be delightful to use. Will users face any issues, can there be some changes done to make the experience even more delightful?
    

- **Recommendations at both levels**:  
	Level 1: Fixes and suggestions marked on Bugherd, along with basic wireframes for corrected implementation  

	Level 2: Suggestions marked here, with rough wireframes to explain functionality.

## Heuristic Principles and Usability Checklist

### Visibility of system status

Visibility of system status refers to how well the state of the system is conveyed to its users. Communicating the current state allows users to feel in control of the system, take appropriate actions to reach their goal, and ultimately trust the system.

Ideally, systems should always keep users informed about what is going on, through appropriate feedback within reasonable time.

  

-   Feedback - Whenever users interact with a system, they need to know whether the interaction was successful. Did the system actually catch that button press or was it busy with something else and it ignored it? Did the request go through? (One reason users have these questions is that they have been burned before by technology that didn’t work properly. However, even when the happy day of bug-free technology arrives, people will still wonder if they really clicked or tapped correctly.)
    

  

### Match between system & real world or user’s mental model

The system should speak the users' language, with words, phrases and concepts familiar to the user, rather than system-oriented terms.
Follow real-world conventions, making information appear in a natural and logical order.

  

### Error prevention

Good error messages help the user understand what went wrong and how it could be fixed. 
However, we should take steps to prevent the errors from occuring in the first place.

-   Either eliminate error-prone conditions or check for them and present users with a confirmation option before they commit to an action.
    
-   Implement helpful constraints which could prevent the user from entering incorrect data into the system which would otherwise cause an error.
    
-   Suggest actions and input elements wherever possible to guide users towards the correct use of an interface.
    
-   Offer reasonable defaults that are likely to fit real-world goals
    
-   Automatically format user input to match system expectations wherever possible.  
      
    

### User control & freedom

Users should be able to navigate to all the parts of the system with ease and never get the feeling of being lost.

Users often choose system functions by mistake and will need a clearly marked "emergency exit" to leave the unwanted state without having to go through an extended dialogue. A User may also need to undo and redo actions to recover from these mistakes.

  

### Consistency & standards

Users should not have to wonder whether different words, situations, or actions mean the same thing. Similarity helps users predict various outcomes of the system. The system should follow a consistent vocabulary and a design standard that are structured according to most users’ mental model.

Elements such as fonts, buttons, links, colours, font sizes, etc. should be consistent within the entire system.

  

### Recognition rather than recall

Minimize the user's memory load by making objects, actions, and options visible. The user should not have to remember information from one part of the dialogue to another.

Instructions for use of the system should be visible or easily retrievable whenever appropriate. By making information and interface functions visible and easily accessible.

  

### Flexibility & efficiency of use

Users need quick and efficient ways to speed up their interactions with the system. They should have easy access to functionality that they need the most.

In some cases, users can even benefit from ambient information related to what action is being taken, helping them make quicker and better decisions.

Flexible Shortcuts or Accelerators may often speed up the interaction for users such that the system can cater to both inexperienced and experienced users.

  

### Aesthetic and minimalist design

Users can only process limited information at a time. Sometimes, the interface is too cluttered with too much information and a lack of hierarchy, making it difficult for the user to understand.

The user should only see information that is relevant to the user. Removing content may seem like the best way out even though it is not always the right approach.

  
  

### Help recognize & recover from errors

Some errors can’t be prevented, and when something does goes wrong, the user should be able to diagnose the problem and find a solution without leaving the system.

Error messages should be expressed in plain language (no codes), precisely indicate the problem, and constructively suggest a solution.

  

### Help & documentation

Even though it is better if the system can be used without documentation, it may be necessary to provide help and documentation. Any such information should be easy to search, focused on the user's task, list concrete steps to be carried out, and not be too large.

A user’s perception and understanding of affordances might vary according to their ability, goals, beliefs, context and past experiences.

  

### Affordance

Affordance refers to the actions a user perceives to be possible, distinct from those which are actually possible. Desired actions cannot be carried out if the object does not afford it, and afforded actions might not be carried out if the user does not perceive they are possible.

  

In software interfaces managing affordances is critical, a user might perceive possible actions based on the properties of interface objects. Giving incorrect visual cues can ruin user experience and lead to frustration.

  

### Simplicity

We want our products to have a level of complexity without being complex, and prioritize feature development over learning and the user experience.

Information available to the user should be as simple as possible and task focused.

  

-   Remove needless, risky and distracting features which don’t add much value to the overall system.
    
-   Identify user patterns and organize material around them. Frame your terms of reference. Don’t force the user to learn something.
    
-   Organize around patterns of use and not frequency. Look for behavior that signals a pattern. Experts will look for additional features, while mainstream audiences will need easy access to what they need.
    

  
  

### Structure

Structure is concerned with how content is organized, how it’s prioritized, how much of it. It also allows users to move through site content efficiently and effectively.

A good structure should be something that's flexible, and can accommodate growth and adapt to change. There should be a focus on the relationships between content, which categories go together, and which don’t, what are the sequence of steps that can fit together, how to move through the information, based on user needs and expectations.

  

### Accessibility

Accessibility enables people with disabilities to perceive, understand, navigate, interact with, and contribute to the web.

  

-   Color should not be used as the only visual means of conveying information.
    
-   Ensure sufficient contrast between text and its background.
    
-   Provide visual focus indicator for keyboard focus.
    
-   Forms and input fields should always have labels and borders.
    
-   Primary information should always be visible, secondary information should be shown on hover.
    

  

### Copy Issues

Information displayed should be in a clear and simple language. Users should be able to understand the meaning of the information, else it is of no use.

-   Only necessary and meaningful information needs to be displayed to the user.
    
-   Avoid using redundant words and do not over-communicate information repeatedly.
    
-   Avoid using technical jargon.
    
-   Avoid negative words.
    
-   Avoid uppercase text.
    
-   Use Progressive Disclosure Approach where detailed information related to a message that the user may not want to see is hidden within a Show/Hide section.
    
-   Place information where it belongs.


