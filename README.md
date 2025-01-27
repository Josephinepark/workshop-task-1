##### workshop-task-1

# Workshop 1 : Coding Fundamentals

[website link] https://josephinepark.github.io/workshop-task-1/

- I used loops to create a shape resembling a speaker. By utilizing repetitive patterns, I was able to generate circular or radial structures that visually represent the dispersion of sound waves from a speaker.

## Task
[] Sketch using 2D primitive shapes, loops, and random numbers <br>
[] write your own functions and make calls to these functions in your code <br>
[] experiment with at least one new item from the https://p5js.org/reference/

## Notes from the workshop video
coding principles : variables, conditionals, loops, functions, and objects

<three key elements in loops>
- variable / while (x<width)
- exit condition / rect(x,200,23,80)
- increment station / x+=50

<function>
defining : setup / draw
calling : createCanvas / background / fill / noStroke <br>
<br>
Q. why do we need functions? <br>
A. modularity / reusability

## Progress (Experimentation and problem solving)

working with loops

<img width="812" alt="image" src="https://github.com/user-attachments/assets/c73d17da-fe01-45a2-8e41-a042f8259617" />
<br>
<br>
During the process, I experimented with different loop counts and angles to achieve various shapes and sizes, while adjusting colors and transparency to create a more three-dimensional and dynamic design. 
<br>
<br>
<img width="829" alt="image" src="https://github.com/user-attachments/assets/27cdae72-6046-42b0-b811-bb64347e9da0" /> <br>
<br>
<br>
I took the time to experiment with not only loops but also various other functions to explore different possibilities. In addition to repeating specific patterns, I aimed to create more creative outcomes by experimenting with a range of functions.
<br>
<br>
I wanted to try another one, so I tried a new function, mousemoved(). I had an idea to make circles follow the mouse as it moved.
<br>
<br>
<img width="959" alt="image" src="https://github.com/user-attachments/assets/e5e74cd8-2920-4419-8738-2493d5dbe6e6" /> <br>
<br>
<br>
It was working as different as I have intended so I have used the chatgpt to figure out the problem of my codes.<br>
<br>
<br>
My prompt : " How do I need to fix the codes to get the circles to follow when I move the mouse?
<br>
<br>
<img width="407" alt="image" src="https://github.com/user-attachments/assets/67e03cde-e03c-4fe9-ac8a-6f73b80b459c" /> <br>
chatgpt : To make circles continuously follow the mouse movement, the background should not be cleared every frame. If the background() function is called inside the draw() function, the canvas will be overwritten repeatedly, causing previously drawn circles to disappear. To prevent this, the background should be set only once or the background call should be removed. <br>
<br>


<img width="959" alt="image" src="https://github.com/user-attachments/assets/099e96ab-fbef-4aa9-bcd6-6468d3df982b" /><br>
<br>
<br>
After making revisions, I explored how changes in numerical values within the code affected the overall output. By adjusting these values, I observed differences in the size, position, color, and movement patterns of the shapes.
<br>
<br>
<img width="792" alt="image" src="https://github.com/user-attachments/assets/3a7cd76a-4233-4601-b76d-9a742a74670e" /><br>
<br>
<br>
I also experimented with the createButton() and drawGrid() functions. I followed several YouTube tutorials to create a shimmering, mosaic-like screen and tried various colour combinations. By adjusting the number values of (r, g, b), I was able to observe how different numbers resulted in different colour outputs.

While working with createButton(), I learned how number values influence the button's position. This helped me understand how to precisely control the placement of interface elements.

Additionally, I explored the difference between having strokes and not having them, which provided insights into how visual elements can be structured. I also discovered ways to make the shapes within the grid appear to shimmer dynamically. These experiments helped me gain a deeper understanding of how visual elements interact with each other.
<br>
<br>
<img width="809" alt="image" src="https://github.com/user-attachments/assets/e700767b-2ce7-4112-bea6-1f0f69341edc" /><Br>
<br>
<br>


[p5.js editor] 

https://editor.p5js.org/Josephine003/full/QtJf-J3Vd 

[using MouseMoved]

https://editor.p5js.org/Josephine003/full/eJe0m2mwP

[twinkle]

https://editor.p5js.org/Josephine003/full/IaR9w6_FM


## codes
<img width="595" alt="image" src="https://github.com/user-attachments/assets/3a0e1d7b-9b7d-4809-a33c-53f3bdf395cc" /> 
<br>
<br>
<img width="602" alt="image" src="https://github.com/user-attachments/assets/80dde402-83a2-4070-a9e2-dd5f51283e63" />
<br>
<br>
<img width="433" alt="image" src="https://github.com/user-attachments/assets/96027c29-3096-4f36-9836-17f527d4d805" />


## Future Development

Through this workshop, I have learned many new things. Through various experiments, I realized that even small numerical changes in the code could significantly impact the outcome. I plan to explore different value combinations to achieve the most optimal visual results.

In particular, the workshop task I created using loops has great potential for further development. I would like to experiment with different colours for each line and eventually make the lines move randomly within the array. I believe that such enhancements would make the visuals more dynamic and engaging. Through these additional experiments, I hope to create more creative and interactive visual compositions in the future.

## Reference / other sources that helped me
<br>
https://www.youtube.com/watch?v=cnRD9o6odjk<br>
<br>
https://www.youtube.com/watch?v=k8gIvG_OmvE<br>
<br>
https://www.youtube.com/watch?v=clzROXdolGU<br>
<br>
https://editor.p5js.org/jiz125/sketches/h6zNkmb6C
- this is where I got help from using the drawGrid().
