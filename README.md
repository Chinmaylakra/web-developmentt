<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>To-Do List</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <div class="todo-list">
            <h1>To-Do List 📝</h1>
            <div class="input-container">
                <input type="text" id="taskInput" placeholder="Add your task">
                <button onclick="addTask()">Add</button>
            </div>
            <ul id="taskList">
                <li>
                    <input type="checkbox" checked disabled>
                    <span class="completed">Complete college project</span>
                    <button class="delete-btn" onclick="deleteTask(this)">✖</button>
                </li>
                <li>
                    <input type="checkbox" checked disabled>
                    <span class="completed">Do a summer internship</span>
                    <button class="delete-btn" onclick="deleteTask(this)">✖</button>
                </li>
                <li>
                    <input type="checkbox">
                    <span>Learn Full-stack</span>
                    <button class="delete-btn" onclick="deleteTask(this)">✖</button>
                </li>
            </ul>
        </div>
    </div>
    <script src="scripts.js"></script>
</body>
</html>

.
.
..

.
.

 css 

 body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    background: #2c3e50;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.container {
    background: #ecf0f1;
    border-radius: 10px;
    padding: 20px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.todo-list {
    text-align: center;
}

.todo-list h1 {
    margin-bottom: 20px;
}

.input-container {
    display: flex;
    justify-content: center;
    margin-bottom: 20px;
}

#taskInput {
    width: 200px;
    padding: 10px;
    border: 1px solid #bdc3c7;
    border-radius: 5px;
}

button {
    background: #e67e22;
    border: none;
    padding: 10px 15px;
    margin-left: 10px;
    color: #fff;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background: #d35400;
}

ul {
    list-style-type: none;
    padding: 0;
}

li {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 10px;
    background: #fff;
    margin-bottom: 10px;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

li span {
    flex-grow: 1;
    margin-left: 10px;
}

li .completed {
    text-decoration: line-through;
    color: #bdc3c7;
}

.delete-btn {
    background: none;
    border: none;
    color: #e74c3c;
    cursor: pointer;
    font-size: 16px;
}

.delete-btn:hover {
    color: #c0392b;
}
.
.
.
.
.
.
java script
function addTask() {
    const taskInput = document.getElementById('taskInput');
    const taskText = taskInput.value.trim();

    if (taskText !== '') {
        const taskList = document.getElementById('taskList');
        const newTask = document.createElement('li');

        newTask.innerHTML = `
            <input type="checkbox">
            <span>${taskText}</span>
            <button class="delete-btn" onclick="deleteTask(this)">✖</button>
        `;

        taskList.appendChild(newTask);
        taskInput.value = '';
    }
}

function deleteTask(element) {
    const taskItem = element.parentElement;
    taskItem.remove();
}
