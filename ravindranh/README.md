# Exercise Reflection

Answer the following prompts in preperation for our class discussion about this exercise.

## Explain your decisions to create your task topic files. What was your reasoning?

- I went through the webpages and tried to identify content that was instructional in nature. From reading the content available in each webpage, I tried to comprehend the overall message the content was trying to convey. 
- In the **Student Addresses** webpage, there were instructions on how to add addresses in the MyPack portal, along with step-by-step instructions on how to edit addresses as well. These two groups of instructions were clearly split, along with additional information on the types of addresses available. 
- Similarly, in the **Personal Information and Privacy** webpage, there were distincly classified intructions on how to view and restrict personal information. 
- After identifying the 4 topics mentioned in the webpages from the instructional language and usage of imperative action verbs, I decided to base my task topics on them.

## Explain your decisions to translate the tasks from the website, noting any changes to the original. What was your reasoning?

The website content has preconditions and contextual information mixed with procedural information,  and uses distinct visual elements to separate the background info from the main steps. To translate the same into DITA,I separated the contextual and prerequisite info using the <context> and <prereq> tags, before including the main steps insdie the <taskbody> tag. This way, I seperated the background and the motivations from the main task, and established the staging, coaching, and alerting philiosphies effectively. 

## Explain your difficulties. What parts of the process created some pain points for you? Why?

I did not find major impediments in translating the tasks into DITA elements, as the content in the webpage was pretty straightforward. The only challenge, if any, was to include critical information like the address types, FERPA rules, and SEVIS address requirements for foreign students into the DITA structure, without compromising on the primary tasks or causing ambiguity, or disrupting the editorial workflow.  

## How did you overcome those pain points?

I overcame the pain points by keeping the steps concise, structuring the DITA workflow to clearly separate the primary tasks from pre-conditions, and background info. I also leveraged DITA elements such as list, step example, and post req tags to ensure no information was left out. With the help of the UI control tag, I also made sure that I wasnt compromising on the visual quality of the webpage while transalting the content into DITA structure. 




