---
layout: post
title: "Final Project: Todo: XYZ"
date: 2021-12-12
---

# Final Project: Todo: XYZ

- **Link to code base: [Final Project](https://github.com/zhuxinyishcn/NEUSEA-XinyiZhu/tree/main/Todo_List)**
- **Link to APK: [Andriod APK](https://github.com/zhuxinyishcn/NEUSEA-XinyiZhu/blob/main/Todo_List/app/debug/app-release.aab)**
- **Link to published Alpha on the Play Store: [Alpha on the Play Store](https://play.google.com/apps/testing/edu.neu.mad_sea.xinyizhu.lesson2_1)**

# APP ICON and APP NAME

<img src="https://raw.githubusercontent.com/zhuxinyishcn/CS5520-Project/gh-pages/_screenShot/final_todo_1.PNG" alt="drawing" width="300"/>

# Features

- Core Features
- Notification Callback
- Search Todo Items / Contents
- Drag and Move Todo Item
- Export a ToDo to another app

## Core Features

1. Users could create a to-do with some detailed information and set up a time to remind himself.
2. User could setup the tag for the todo (ex: Important, urgent, normal)
3. User can click the mark icon to complete and also sometimes unclick it to remind him to continue
4. User could swipe right to complete delete/ complete this task in the list
5. All todo items save into the database and persistent by the database so a user won't lose their data
6. Users could also update their title and details from the list in case task changes.
   <img src="https://raw.githubusercontent.com/zhuxinyishcn/CS5520-Project/gh-pages/_screenShot/final_todo_10.PNG" alt="drawing" width="300"/>
   <img src="https://raw.githubusercontent.com/zhuxinyishcn/CS5520-Project/gh-pages/_screenShot/final_todo_11.PNG" alt="drawing" width="300"/>
   ### Below is a small demo video to understand
   [![IMAGE ALT TEXT HERE](https://raw.githubusercontent.com/zhuxinyishcn/CS5520-Project/gh-pages/_screenShot/final_todo_2.PNG)](https://youtu.be/Uay1g29yA40)

## Notification Callback

1. Make my notifications can be clickable and the reminder message should be more encourage them to complete their task
2. By clicking the notification, it should automatically refer to the todo application
   ### Below is a small demo video to understand
   [![IMAGE ALT TEXT HERE](https://raw.githubusercontent.com/zhuxinyishcn/CS5520-Project/gh-pages/_screenShot/final_todo_4.PNG)](https://youtu.be/x4pncEm_wBo)

## Search Todo Items / Contents

1. User has the chance to search for some important todo, either is the contents in the detail or the title of the todo item.
2. It is using an android filterable API for recycling views, so it is searched instantly. There is no step for the user to hit the entrance then start the search.
   ### Below is a small demo video to understand
   [![IMAGE ALT TEXT HERE](https://raw.githubusercontent.com/zhuxinyishcn/CS5520-Project/gh-pages/_screenShot/final_todo_5.PNG)](https://youtu.be/uhgLjXkT2ps)

## Drag and Move Todo Item

1. User could put the most relevant to-do item on the top of the list and reorganize the list by shifting and rotating the to-do item.
2. User also could put the new todo item on the top of the list since the newest todo item will be on the bottom of the list.
   ### Below is a small demo video to understand
   [![IMAGE ALT TEXT HERE](https://raw.githubusercontent.com/zhuxinyishcn/CS5520-Project/gh-pages/_screenShot/final_todo_6.PNG)](https://youtu.be/S-kkUUwSy5Q)

## Export a ToDo to another app

1. User can share the todo Item with his friends and request them to remind them as a safety net.
2. Users can bring the most important thing as an SMS message to his contact to remind him.
   ### Below is a small demo video to understand
   [![IMAGE ALT TEXT HERE](https://raw.githubusercontent.com/zhuxinyishcn/CS5520-Project/gh-pages/_screenShot/final_todo_7.PNG)](https://youtu.be/WEb52KmBNMk)

## Issues

- Dragging and dropping in the list does not preserve the position after operation.
