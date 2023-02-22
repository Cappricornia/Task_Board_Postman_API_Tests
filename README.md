# The ***Task Board*** System 📌
=======================================
## RESTful API: Postman API Tests 🧪 ✔️
=======================================
#### ☑️ ***Task Board*** is a simple information system for managing tasks in a task board. Each task consists of title + description. 
#### ☑️ Tasks are organized in boards, which are displayed as columns (sections): Open, In Progress, Done. 
#### ☑️ Users can view the task board with the tasks, search for tasks by keyword, view task details, create new tasks and edit existing tasks (and move existing tasks from one board to another).
#### ☑️ The app does not have a persistent database storage, so you can reset it by a simple restart 

#### 🔻 The following endpoints are supported:
#### ➡️	GET /api – list all API endpoints
#### ➡️	GET /api/tasks – list all tasks (returns JSON array of tasks)
#### ➡️	GET /api/tasks/id – returns a task by given id
#### ➡️	GET /api/tasks/search/keyword – list all tasks matching given keyword
#### ➡️	GET /api/tasks/board/boardName – list tasks by board name
#### ➡️	POST /api/tasks – create a new task (post a JSON object in the request body, e.g. {"title":"Add Tests", "description":"API + UI tests", "board":"Open"})
#### ➡️	PATCH /api/tasks/id – edit task by id (send a JSON object in the request body, holding the fields to modify, e.g. {"title":"changed title", "board":"Done"})
#### ➡️	DELETE /api/tasks/id – delete task by id
#### ➡️	GET /api/boards – list all boards
==============================================================================

#### >>> List all boards ✔️

![test1](https://user-images.githubusercontent.com/90700181/220757439-e37c2fbf-4d3a-49ed-a5b1-b6388e9c01df.png)

#### >>> List the tasks by board name ***Done*** ✔️

![test2](https://user-images.githubusercontent.com/90700181/220757694-b6db33d6-6185-4c43-a45c-dc15374cc5f5.png)

#### >>> Create task ✔️

![test3](https://user-images.githubusercontent.com/90700181/220757790-4179a6fc-9f39-4701-be09-d947825effc6.png)

#### >>> Edit created task ✔️

![test4](https://user-images.githubusercontent.com/90700181/220757913-df47bacd-6e6e-4040-a644-44797b2bb16c.png)

#### >>> Delete existing task ✔️

![test5](https://user-images.githubusercontent.com/90700181/220757989-e3c7e092-b71e-42f2-8e9e-a272ca812073.png)

#### >>> RUN ALL TESTS ✔️

![tests_postman](https://user-images.githubusercontent.com/90700181/220758186-a17c6a57-831e-4a2d-90ac-fc8b31a46b0a.png)


