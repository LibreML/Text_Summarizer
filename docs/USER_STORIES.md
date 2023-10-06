# User

---

| ID--USR-1           | As a Researcher i want to be able to summarize a paper i am reading to save time. |
| ------------------- | --------------------------------------------------------------------------------- |
| Description         | - **User:** Researcher                                                            |
|                     | - **Functionality:** Summarize text in shorter words than the original text.      |
|                     | - **Goal:** Be able to Summarize text                                             |
| Acceptance Criteria | 1. Plan and Design the architecture for the language model                        |
|                     | 2. Implement the architecture.                                                    |
| Notes               |                                                                                   |
| Tasks               | - [ ] Create Design Documents for Model Architecture template                     |
|                     | - [ ] Implement Model Architecture                                                |

---

| ID--USR-2           | As a Novice Computer User, i want this program to be a Graphical One, so that i can use the program. |
| ------------------- | ---------------------------------------------------------------------------------------------------- |
| Description         | - **User:** Novice Computer User                                                                     |
|                     | - **Functionality:** Create a UI for the Application.                                                |
|                     | - **Goal:** Users should be able to interact with the program via a UI                               |
| Acceptance Criteria | 1. Create Layout with all widgets in TKinter                                                         |
|                     | 2. Implement functionality for connecting to the backend                                             |
| Notes               |                                                                                                      |
| Tasks               | - [ ] Create Layout and widgets for the program                                                      |
|                     | - [ ] Connect to backend model                                                                       |

---

| ID--USR-3           | As a Writer, i want to summarize my writings to a specific number of words. So that i have fine grained control of how short my text should be |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| Description         | - **User:** Writer                                                                                                                             |
|                     | - **Functionality:** Instruct the Model to produce x words as the output.                                                                      |
|                     | - **Goal:** Ability to specify the number of words the output text should be.                                                                  |
| Acceptance Criteria | 1. Implement backend supported functionality                                                                                                   |
|                     | 2. Implement UI functionality so the user can specify the number of words                                                                      |
| Notes               |                                                                                                                                                |
| Tasks               | - [ ] Implement Backend support for specified number of words in the summarization.                                                            |
|                     | - [ ] Connect backend functionality to UI                                                                                                      |

# Developer

---

| ID--DEV-1           | As a Developer, i want to be able to summerize text via a REST API. |
| ------------------- | ------------------------------------------------------------------- |
| Description         | - **User:** Developer                                               |
|                     | - **Functionality:** REST API                                       |
|                     | - **Goal:** Send GET HTTP requests to summerize text.               |
| Acceptance Criteria | 1. Implement /summerize endpoint                                    |
|                     | 2. Make endpoint contact backend.                                   |
| Notes               |                                                                     |
| Tasks               | - [ ] Implement Backend support endpoint with GET method.           |
|                     | - [ ] Get Server working on port 8000.                              |
