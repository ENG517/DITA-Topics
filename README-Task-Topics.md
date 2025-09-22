# DITA Task Topic Exercise - Identifying and Creating Task Topics

After you have read the readings, complete this exercise on your own new branch of work.

**Objective**: Identify task topic content on NCSU's Student Services website. Translate that content as task topic `.dita` XML files.

## 1. Setting Up Your Exercise Folder

1. Create a new branch with the following naming scheme: `PRAC/Tasks-lastname-exercise`.
2. Copy and paste the `COPYME-DONOTUSE` folder.
    - **NOTE**: You can ignore the assets folder for now, but don't delete anything in the folders, such as the `.keep` files.
3. Rename the newly copy-pasted folder with your lastname and firstname initial in all lowercase letters.
    - **EXAMPLE**: My name is "Chris Lindgren", so my folder name will be `lindgrenc`
4. Now, start topic modeling!

## 2. What to Do

1. Review the following two pages from NCSU's Student Services:
    - ["Personal Information and Privacy"](https://studentservices.ncsu.edu/resources/personal-information-and-privacy/).
    - ["Student Addresses"](https://studentservices.ncsu.edu/resources/personal-information-and-privacy/student-addresses/)
2. In your new branch and work folder, create as many task topics as you think necessary to account for task topic content across these two pages. You will do so by completing the following steps:
    1. Create each task topic `.dita` file by copying and pasting the provided skeleton `.dita` file for task topics in the root of this repo: `t_scary_skeleton.dita`.
    2. Move the newly copied-pasted `.dita` file to your personal work folder.
    3. Rename the new file with the following filenaming scheme for your task topics: `t_imperativeverb_verbobject.dita`.
      - **EXAMPLES**: `t_make_latte.dita`, `t_steam_milk.dita`, or `t_prepare_beans.dita`
3. As you work on this exercise, be sure to:
    1. Take notes about your experiences in ***your folder's*** `README.md` file.
    2. Commit and push changes to your branch often with meaningful commit messages.
4. When you are done, create a Pull Request (PR) and copy and paste your reflection from the `README.md` file.
5. Submit your PR to Moodle.

## 3. Basic Tips to Complete the Exercise

### Identify existing task content

Tasks often include the following information (Bellamy et al., p. 220):

- Numbered lists
- Describes how to do something
- Verb-based titles or headings. Yet, do not rely on this guideline solely, because sometimes conceptual and reference genres fit this characteristic sometimes, e.g., "Understanding cat behavior."

### Review the Guidelines for Writing Task Topics

Know the difference between different kinds of content and always be sure that the element you use to wrap the content is the right element.

### Write one task per topic

Think in terms of smaller topic files with procedures broken down into component sections that are potentially small enough to be reused.

- For example, instead of appending related tasks to an already long topic, make them stand on their own.
- Use organization and reltable linking in order to connect related topics.
- Recognize the difference between "processes" and "procedures" as they differ primarily in terms of breadth.

### Create tasks and subtasks to organize long procedures

Even tasks that may seem like they are all one coherent task should be broken up into smaller topical units. This may not be the case in this assignment, but it is always good to consider the following questions to mitigate this issue:

- Is the task topic over 10 steps long? Reconsider and put in smaller task topics.
- Feel like you want to include a new step section and restart the numbering? You really need a new task topic.

**Example**: Identifying manageable topics for a user goal like "Managing your Zotero Library" when using a citation manager like Zotero:

- Managing your Library  (too big! break it down into topics)
  - Library (concept)
  - Building your library (process)
  - Adding an item  (task)
  - Item Types (reference)
  - Book (concept)
  - Organizing your library (process)
  - Collections (concept)
  - Adding a collection (task)