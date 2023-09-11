# Task 2 
## Bug 1
- Problem: Next button not working on JobDetails Form
- Solution: Removed the ```jobPosition``` from the yup validation

## Bug 2 
- Problem: Props were not passed in DisplayCard componenets present in HomeLayout and Preview card not working
- Solution:
  - Used the context api to retreive the data
  - ![image](https://github.com/tanwarAalok/TIF_-React-Developer-Hiring-Task-2-Repository/assets/78805153/bc0b3a75-ea80-472c-9178-f9f5f5832172)
  - Then passed to DisplayCard
  - ![image](https://github.com/tanwarAalok/TIF_-React-Developer-Hiring-Task-2-Repository/assets/78805153/24845412-5660-4d1a-af2e-55644fee29b4)
  - Also updated the state in ```onSubmit`` on each form like
  - ![image](https://github.com/tanwarAalok/TIF_-React-Developer-Hiring-Task-2-Repository/assets/78805153/f6c546d0-d308-4691-b125-33311615b1b0)


