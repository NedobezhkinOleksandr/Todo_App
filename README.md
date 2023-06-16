# Todo App

- [Todo App] - https://nedobezhkinoleksandr.github.io/Todo_App/;

- Project related to Todo task list, where you can plan your tasks, and if you complete them, to mark as completed;

- Once you comes to this App, you will see input block, where you can write the task, what you are planning to do;

- Once you write your task, press Enter, then you will see your task under input block, with 1 radio-button, name of your task and on hover - cross-button to delete your task;

- On pressing radio-button, you will mark your task as 'completed', task's title will be crossed and blured;

- Once you have at least 1 completed task, you will find new button 'Clear Completed' on the right-bottom corner of the App, and by pressing it you will delete ALL completed tasks;

- You can see, on center-bottom of the app, tabs: All, Active, Completed. Every tab will show you tasks related to names of this tabs: 
  1) Active = Not completed tasks;
  2) Completed = Completed tasks; 
  3) All = Completed/not completed tasks;

- On input block, you can see arrow, if you have at least 1 task. Which is manipulating with all of your tasks, if you press it, and you have at least 1 'completed' and 2 'not completed', it is making all your 'not completed' - 'completed', and if all of your tasks are 'completed' - 'not completed';

- Have a counter, which is showing how many tasks left to do;

- You will see animation(spinner) on each manipulation with your tasks;

# Code info

- Main technology in use is React-JS;

- Components which in use: 
  1) Header - to display and use input block;
  2) TodoItem - separate section for each of your task;
  3) TodoList - collecting all TodoItem components in one place together under input block;
  4) Footer - displaying task left to do, tabs and button 'Clear Completed';
  5) Loader - additional component to show main loader on uploading your tasks from server;
  6) LoadingContext - to use hook useContent;

- API methods in folder api in todos.ts;

- Types folder with required interfaces in Todo, displaying Errors and FilterType to filter my tasks as required;

- And main file App.tsx where our project rendering;



- Code's author:

  Nedobezhkin Oleksandr;

- Contact info:

  tel: 00380730752256;
  e-mail: nedobezhkin_ad@yahoo.com;
  github page: https://github.com/NedobezhkinOleksandr.
