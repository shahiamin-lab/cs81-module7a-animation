# Reflection – Module 7A Loading Animation

**What part of the code was most confusing and why?**  
The most confusing part of the code was understanding how the modulo operator (%) was used to loop through the frames array. At first, it was not obvious how index % frames.length prevents the animation from going out of bounds. After stepping through the code, I realized it allows the animation to repeat smoothly without resetting the index manually.

**How does the animation help visualize asynchronous behavior?**  
The animation clearly shows asynchronous behavior because the page does not freeze while the loading animation runs. The setInterval function allows the browser to continue responding while the animation updates at fixed time intervals. This demonstrates how JavaScript can perform repeated tasks over time without blocking the main thread.

**What did you change or improve, and what effect did it have?**  
I added a feature that changes the background color once the animation finishes. This improvement provides visual feedback that loading is complete and makes the interaction feel more polished. It also helped reinforce how DOM elements can be modified dynamically after an asynchronous loop ends.
