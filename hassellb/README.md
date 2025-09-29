# Exercise Reflection

Answer the following prompts in preperation for our class discussion about this exercise.

## Explain your decisions to create your task topic files. What was your reasoning?

The first thing I did for each webpage was pick out which sections are tasks, which are conceptual, and which are references (since we're just focused on tasks, I set aside the sections that weren't). Using the readings, I defined a task as a clear action-oriented procedure that satisfies a user goal. Both pages had multiple tasks. For example, a user will approach the Personal Information and Privacy page to either view their info or restrict it, or both. That involves a two tasks: to view and restrict. The user will approach the Student Addresses page to either add or update their addresses, or both. This also involves a task to add and a task to update addresses. I created a separate DITA file for each task.

## Explain your decisions to translate the tasks from the website, noting any changes to the original. What was your reasoning?

For the "View Your Personal Information" task, I separated the initial directory path into two steps to make the flow of action clearer. The default page for MyPack Portal _is_ the Student Homepage, so I just added that as additional info.

I changed the title of the task from "Directory Information Privacy Settings" to "Restrict Directory Information" so the user has a clear view of what the procedure specifically entails since the original title implies there's multiple settings even though it only covers directory information restriction. In the same task, I found steps 4 and 5 to be convoluted, so I reformatted step 4 to clearly show the choices it presents and split step 5 into a series of substeps. 

I didn't change much for the "Add or Update Addresses" tasks other than step 5 for adding an address which, similarly to step 4 of the "Restrict Directory Information" task, I reformatted to clearly show the presented choices.

## Explain your difficulties. What parts of the process created some pain points for you? Why?

The only real issue I ran into was deciding how to communicate locational information. Since each `<cmd>` element should begin with an imperative verb, the locational information must be stored elsewhere, which I used th `<info>` tag for. Since the style guide (if that's the right word for it) we have dictates the `<info>` tags must come after the `<cmd>` tags, it felt a little strange:

"In the left-hand navigation menu, select **Addresses**" vs "Select **Addresses**, located in the left-hand navigation menu"

I naturally prefer the first option as a writer and user, so it felt weird to make that change.

## How did you overcome those pain points?

I just rolled with it. Every style guide has its specifications for a reason. It required editing some language here and there, but nothing too major. Overall, the process went very smoothly.
