<template>
  <div class="home">
    <div class="container">
<h1>My Todo List</h1>

<p>This is an application for people that wants to remind them self about something they need to do in the future ^^.</p>
<p>Feel free to use this app, and to start to start the app just go to "My Apps" Section</p>
    </div>
  </div>
</template>

<style>
.container {
  max-width: 600px;
  margin: 0 auto;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
  color: #42b983;
  background-color: #545454;
}

h1 {
  text-align: center;
  margin-bottom: 20px;
  font-size: 2rem;
}

.form {
  display: flex;
  margin-bottom: 20px;
}

.form-input {
  flex: 1;
  padding: 10px;
  font-size: 1.2rem;
  border-radius: 5px 0 0 5px;
  border: none;
}

.form-btn {
  padding: 10px;
  font-size: 1.2rem;
  background-color: #37f026;
  color: #fff;
  border: none;
  border-radius: 0 5px 5px 0;
  cursor: pointer;
}

.todo-list {
  list-style: none;
  margin: 0;
  padding: 0;
}

.todo-item {
  display: flex;
  align-items: center;
  margin-bottom: 10px;
  padding: 10px;
  border-radius: 5px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.todo-left {
  flex: 1;
  display: flex;
  align-items: center;
}

.todo-checkbox {
  margin-right: 10px;
  cursor: pointer;
}

.todo-text {
  font-size: 1.2rem;
}

.todo-delete-btn {
  padding: 10px;
  font-size: 1.2rem;
  background-color: red;
  color: beige;
  border: none;
  cursor: pointer;
  transition: transform 0.2s ease-in-out;
}

.todo-delete-btn:hover {
  transform: scale(1.1);
}

.show-btn {
  display: block;
  margin: 0 auto;
  padding: 10px;
  font-size: 1.2rem;
  background-color: #b3b2af;
  color: #fff;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}
body{
  background-color: #242424;
}
</style>