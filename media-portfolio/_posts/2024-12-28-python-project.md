---
layout: post
title: "Building an Interactive Biology Learning App"
date: 2024-12-28
categories: [Projects, Biology, Programming]
---
**Building an Interactive Biology Learning App with Event-Driven Programming**  

In this project, I created an interactive biology app using JavaScript's event-driven programming model. The app is designed to help users explore the differences between prokaryotic and eukaryotic cells, with detailed screens for specific cell structures like the nucleus, mitochondria, ribosomes, and more. The app also features a humorous take on encouraging biology appreciation. You can explore the project [here](https://studio.code.org/projects/applab/abYXG6WYkMyRERk_SlNMOOZVKxCZrvAr8k07cYI4dpE/edit).  

### Overview of Features  

1. **Screen Navigation**  
   The app uses `onEvent` functions to handle user interactions. Each button click triggers the `setScreen` function, which navigates to the corresponding screen. For example:  
   - The `"ProCellSelect"` button leads to the `"Prokaryotic"` screen.  
   - From there, users can explore specific structures like fimbriae, ribosomes, flagella, and the nucleoid region.  

2. **Interactive Cell Structure Exploration**  
   Each screen provides details about a specific cell structure:  
   - For prokaryotic cells, users can learn about structures like fimbriae and the nucleoid region.  
   - For eukaryotic cells, users can explore organelles such as the mitochondria, lysosomes, and vacuoles.  

   Return buttons on each detailed screen allow users to navigate back to their starting point (prokaryotic or eukaryotic overview screens).  

3. **Dynamic Feedback for Humor**  
   A `"HateBio"` screen is triggered when the `"No"` button is clicked, accompanied by a humorous response to dissuade dislike of biology. When users interact with the `"hatebioanswer"` field, it displays a custom message (`"Wrong! Bio is awesome!"`) and updates an image element to `"angry.png"`. This feature adds a playful touch to the app.  

### Technical Concepts  

1. **Event-Driven Programming**  
   The app uses `onEvent` functions extensively to handle user interactions. This makes the app highly responsive to user actions, enabling smooth navigation and interactivity.  

2. **Dynamic Property Updates**  
   The `setProperty` function is used to change text and images dynamically. For example, updating the `"bioawesome"` text and `"rahhhhh"` image provides instant feedback to user input.  

3. **Modular Design**  
   Each screen is dedicated to a specific function or content, ensuring clarity and easy navigation. Return buttons maintain a structured flow, preventing users from feeling lost.  

### Lessons Learned  

This project demonstrates how to create interactive educational tools using event-driven programming. The clear separation of content into screens, combined with dynamic feedback, makes learning both engaging and accessible.  

By applying JavaScript fundamentals to a real-world educational challenge, I gained valuable experience in UI/UX design and coding best practices. This app shows how programming can be a powerful tool for making complex topics like cell biology more approachable and fun!  

Explore the app in action [here](https://studio.code.org/projects/applab/abYXG6WYkMyRERk_SlNMOOZVKxCZrvAr8k07cYI4dpE/edit).