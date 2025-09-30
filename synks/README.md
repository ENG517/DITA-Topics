# Exercise Reflection

Answer the following prompts in preperation for our class discussion about this exercise.

## Explain your decisions to create your task topic files. What was your reasoning?
I created 4 task topic files. 

On the personal information and privacy page, there were 2 tasks: 1. View Your personal information which I named "t_view_personal_info.dita", and 2. The header for this one is called "Directory Information Privacy Settings" but the actual task itself is how to update your privacy settings. Since I work in administration at the university, I know that this is almost exclusively referred to as "FERPA", an acronym for the federal legislation mandating students to have an option to refuse to make their name and personal information public in things like graduation programs. Knowing this, and wanting to make a more concise title, I named this task "t_update_ferpa.dita".

For the "Student Adresses" page, I created 2 task topics. On this page, there were two  Header 2's -- one named "address definitions" and another named "add or update an address". I considered "address definitions" to be a reference topic, not a task topic, because it was simply a list of definitions. Under the second header, here were two tasks, each with a numbered list of subtasks. As the header implies, one task was for adding an address, which I named "t_add_address.dita". The other task was for updating an address, which I named "t_update_address.dita"

So, in summary, I created for tasks:
- t_view_personal_info.dita
- t_update_ferpa.dita
- t_add_address.dita
- t_update_address.dita


## Explain your decisions to translate the tasks from the website, noting any changes to the original. What was your reasoning?
3 tasks were very straightforward -- "add address", "update address" and "update ferpa". All three of these were a clear cut task, all with 6, often identical, steps. As instructed in Dr. Lindgren's video, I added an ID, a title, and a task with 6 steps. It was straightforward. The trickier decision was what to do with "view personal info". I describe in the next response my choices for that.

I made one change to the content of the steps themselves: changed "&" in list in "t_view_personal_info.dita" because the "&" caused a syntax error in DITA.

The 6th step for "update info" was a save step, which was worded as "Be sure to click the green ‘Save’ button to save your changes". This was a change from the final step for "add address" and "update address", which read, simply: "Select the green ‘Save’ button".

I prefer the shorter version, but I kept it as is for now in the attempt to preserve the content in its current form. I added a comment beneath the step to note this, in case we decide it works better to have that command be identical across pages.
>note: As someone who edits this website for my job at the university, I know that we are not meticulous enough to have anyone editing at this level of granularity. We do not use any single source information architecture. Different portions of different pages throughout the website are owned by various employees depending on their responsibilities, and supervised by a webmaster who probably is not paying that much attention to these sorts of things. If you went throughout the entire university website, you could find a million examples of this, probably for things that actually matter more. I only have the ability to edit the couple pages that pertain to my job, and they do not pay me enough to care about the rest of it. But it is useful to think about what I would do if I wanted to try and solve that issue.


## Explain your difficulties. What parts of the process created some pain points for you? Why?
The hardest part was deciding what to do with the "view_personal_info.dita" task. As far as what we've learned about writing good topics, I think you could argue that this one is a little wonky, because it seems to blend reference information (a long unordered list) with a task. Nevertheless, I decided to keep this as a task, because ultimately, it start with one single task: to view or change your personal information, follow x path.

Based on the video's request to only write the tasks and subtasks, I may have gone overboard or missed the mark on this, but in the name of being thorough I decided to organize it in the following way: write the single task, and then add an info block under the task, with the sentence describing the list added into a paragraph inside the info command, followed by the unordered list.

Maybe people will disagree with this choice, and I would accept that. But for the purpose of this assignment, I feel good about my decision to not exclude this. 

## How did you overcome those pain points?
Other than what was described above, deciding what to do and learning how to add an unordered list, nothing was difficult or painful. DITA is pretty cool. It's kind of clunky because of how exhaustive you have to be with naming and ordering every single component. And the fact that I don't have the command names memorized meant I needed to do some quick google searches to find command. For example, I typed in "list" and nothing came up, but after a google search, realized that the command for an unordered list is "ul"....

All that being said, this is pretty cool. DITA seems relatively straightforward and intuitive to me. The learning curve will just be continuing to learn and memorize the conventions. It has a kind of vibe with its rules, however. What I mean by that is it seems like the conventions are applied equally to different commands in what seems like a consistent manner. So once we keep practicing, I do not think it will be difficult to remember the different kinds of conventions and rules for various commands.

