# __Alfat Gilmanshin__

===

## *Junior Frontend Developer*

===

### About Myself:

Hello, my name is Alfat. I'm a beginner Frontend developer.
I'm learning frontend development since 2021.
My first encounter with web development was WordPress.
After that I wanted to study web development more deeply.
Since then I have learned the basic knowledge of layout, javaScript.
I also improve my knowledge in the framework React.js

I hope to improve my knowledge and work on big projects in the future

===

### My Skills

* HTML, CSS, SCSS, BEM
* JavaScript Basics
    + DOM
    + async/aweit
* React.js
    + Hooks
    + Router
    + Rest Api
    + Redux
* Git, Github

===

### Code example:

##### *adding and deleting a contact using asynchronous redux*

```
const addTodo = createAsyncThunk('contacts/add', async contacts => {
  try {
    const { data } = await axios.post('/contacts', contacts);
    return data;
  } catch (error) {}
});


const deleteTodo = createAsyncThunk(
  'contact/delete',
  async todoId => {
    try {
      const { data } = axios.delete(`/contacts/${todoId}`);
      return data;
    } catch (error) {}
  }
);

```

===

### Contacts:

- __Phone__: +7(930)959-22-71, +99(899)200-57-18
- __E-mail__: [gilmalf89@gmail.com]
- __Telegram__: @AlfatGilm

===

### Languages:

* Russin - Native
* Tatar - upper-Intermediate
* English - Intermediate
* Uzbek - Intermediate

===










