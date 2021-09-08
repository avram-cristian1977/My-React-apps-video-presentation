React Hexart devs/tasks manager


Let's say you manage an IT company, you contract public tasks and you gotta settle developers team to attend it.
I create two endpoints with Node Express, one for the devs and one for the tasks. In the frontend I create devs presentation, with those unique specs as a role, ratings, wage or seniority level. The manager will contract a task and according to its requirements, he will create a team of certain devs(charts presentation of for rating and wages). App offers a tool to check devs validity for that specific task, one for checking the ballance between devs salaries and task's budget and also an estimate client satisfaction, according to their ratings. After the manager decides that the deal is worthy, he will send an email to those devs that he selected. The message also contains the type of the project that they are supoused to develop (the selected task). The app includes a time and date functionality and greeting according to that part of the day that you are connected to the app.
	I used Redux toolkit for managing the auth and the enpoint's resources. Therefore implementation of action creators with creteAsyncThunk was mandatory. The sign up component is hidden, it's only one manager. I used chart-js-2 for the ratings and the wages of the developers, react-scroll for scrolling to the html element id. I used Corel suite for creating the company logo.



GitGub : https://github.com/avram-cristian1977/React-Hexart-devs-tasks-manager

My Web Resume : www.avram-cristian.ro

Thank you!