>_**ON&OFF**_ <br>
>_1515023 YeBin Moon_ <br>
>_1615003 Dawn Kim_ <br>
>_1733004 RoYoung Kim_ <br>

## Problem Statement

When people want to cook, they search for a recipe. <br>
However, usually people have hard time finding recipes that fit their situation. <br>
For example, there are some situations when someone has no essential ingredient or cooking tool. <br>
The other situation is not enough time to cook. <br>
<br>
Recommending different recipes for each user <br>
depending on the availability of ingredients or cooking tool, and cooking time user wants. <br>
<br>

## Analysis

### User Analysis

- **User Class**
  - Recipe Uploader: Who tries to share the recipe
  - Recipe Reader: Who tries to see the recipe
  - System Manager: Who manage the system

- **Characteristic**
  - [View more](./characteristic.md)

### Task Analysis

- **Uploader’s point of view**
  - Goal
    - Uploading a recipe
  - Preconditions
    - Must know: how to upload my recipe on the website, how to explain my recipe
  - Subtasks
    - Cook for the recipe uploader wants to upload
    - Take pictures while cooking
    - Log in to the website
    - Write a post for the recipe including what ingredients were needed, <br>
      what kind of cooking tools were used and how long the cooking took
    - Divide ingredients by whether they are essential or optional while cooking

- **Reader’s point of view**
  - Goal
    - Finding a right recipe for me
  - Preconditions
    - Must know: what ingredients and cooking tools I have, my preference of the cooking time
  - Subtasks
    - Log in to the website
    - Search reflecting reader's cooking conditions
    - Choose the recipe above all the recipes shown based on the search
    - Click the recipe chosen

- **System Manager’s point of view**
  - Goal
    - Editing the website
  - Preconditions
    - Must know: how to manage the website, contact information of all users
  - Subtasks
    - Look through to find if there is any recipe without cooking condition selected
    - Contact the uploader to edit the recipe
    - Check out system errors

### Domain Analysis

![Diagram](./image/diagram.png)

## Paper Prototype

![After UserTest](./image/afterUsertest.jpg)

- [View more](./paperPrototype.md)
