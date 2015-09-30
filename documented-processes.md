# Improving Capacity with Documented Processes

This worksheet helps you to develop a list of the common tasks staff engage in. Companies will often develop a skills matrix to highlight skills and deficiencies of the individuals on a team; however, this process is focused on the likelihood that someone on the team could train another person to do the job. Instead of looking for people to train, we are looking for processes to codify / document and simplify. We assume competence on the part of the existing team member, but recognise there may be insufficient automation / resources to easily onboard new staff (resulting in skills deficiencies over time).

## Basic Details

- Name -- used for follow-up questions
- Role -- used to aggregate answers from similar roles into a single skills list
- Duration of employment -- how long have you been at the company (assumes that someone who has been at the company for longer will have a more innate understanding of how tasks are completed and therefore may rank things "easier" than they are)

## Task List

What do you do during a typical day at your company?

**What to record?** Any task that takes more than 10-15 minutes should be recorded; any task that takes fewer than 15 minutes, but is an important part of your job should also be recorded. For example: answering incoming phone calls might take 2-3 minutes, but if it's a key part of your job, write it down!

Ideally this activity is completed individually:

- If working on paper, use post-it notes and write own task per post it.
- If working digitally, use a spreadsheet with one row per task.
- For each task note the frequency.
  - At least once per day: "1" for daily.
  - At least once per week: "2" for weekly.
  - At least once per month: "3" for monthly.
  - Rarely: "4" for infrequent.
- For each task, note the severity or risk if this task is not completed corrected:
  - 1 -- Mistakes are not costly, and do not disrupt service to our customers. They're just annoying.
  - 2 -- Mistakes will be visible to our customers, but impact is mitigated because we can easily make adjustments.
  - 3 -- Mistakes are a very big problem, affecting our customers and our business.

Once the individual tasks have been recorded:

- Collect the tasks into a shared space (wall for post-it notes; single spreadsheet for digital).
- Group the activities per role (e.g., "things a developer is expected to do").

## Confidence Rating

For each of the skills listed previously, how confident are you that you could accurately explain the procedures you use to a new co-worker? Rank on the following scale:

- 3 -- It would be difficult to explain this to someone new because the process is not well documented, and the steps are highly variable.
- 2 -- It would be easy to explain it to someone. The process is relatively straight forward, but not very well documented.
- 1 -- It would be trivial to explain it to someone. The process is sufficiently documented / automated.

Assign a "best guess" for your confidence rating to each task. (It's okay if it's not perfect.)

## Assign Tasks

With a good overview of what your team does, it's now time to clean up your processes so that it is easier to complete the tasks, and explain to others how to be excellent at their job. Tasks which are repeated regularly have a better chance of being learned "on the job". Tasks that are infrequent, and which require a high degree of specialised knowledge are difficult to capture in documentation without a lot of effort. Everything in between is an excellent target for your first round of optimisation.

1. Determine the "relative priority" for each task a score by adding the values for:
   - frequency of task
   - severity/risk of incorrect execution
   - confidence rating
2. Sort the tasks according to their relative priority (OR create a histogram). It won't be perfect, but assuming you have a lot of tasks, this is a nice quick way to sort items.
3. Divide the sorted list into approximate thirds (in other words: bell curve): Easily Learned; Requires Assistance; Requires Specialised Experience.

In theory, the middle group (Requires Assistance) is going to contain tasks which are preformed somewhat frequently, are relatively business critical, and which could use some additional documentation / automation. Your team will focus on improving the documentation / automation of these tasks.

4. Scan the three groups and look for tasks which should be automated.
5. Scan "Requires Assistance" and identify items which would benefit from a standardised practice, and which don't already have documentation.
6. Create tickets for the automation tasks, and documentation tasks. Include notes about each task. Where would you find the documentation if it's in a non-obvious place? Does the documentation need to be updated?

For best success, assign an "owner" for the process of getting the documentation cleaned up and assembled into a coherent package for new hires. (Replace the word "owner" with a term that is appropriate for your culture.)

Plan to meet in 2-3 months time to review the list and ensure tasks are sufficiently documented. Plan to complete the whole process once a year.

## Documentation Storage

Typically, HR will own the process of onboarding new hires for basic account creation, but individual teams will likely have their own preferences for storing role-specific documentation. Wherever it is possible to centralise and standardise, do it! Having to look at 32 systems to learn how to do 43 different things is frustrating.

Choose to use a system that is easily edited. This might include Wiki pages (Confluence, GitHub Wiki Pages), a folder of Google Docs, or in-repository documentation (e.g., a README file in the repository).

### Examples

- [The WunderWay](http://way.wunder.io/) -- does not include specific tech documentation (e.g., how to complete a deployment), but does give an overview of how the company works
- [Warby Parker Data Book](http://www.theoculists.com/the-warby-parker-data-book/) -- article about the internal [GitBook](https://www.gitbook.com/) Warby Parker used to consolidate information
