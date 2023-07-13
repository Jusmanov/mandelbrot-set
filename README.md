# mandelbrot-set
Implemented the Mandelbrot Set on a blank website. The Mandelbrot Set is a fascinating mathematical model that uses the Mandelbrot algorithm to create a beautiful fractal effect. **Made with HTML and JS.**

### Objective:
My goal with this project was to create a beautiful mathematical pattern on a simple website. This pattern is, as mentioned already, called the Mandelbrot Set.

![image](https://github.com/Jusmanov/mandelbrot-set/assets/85308633/eb795d7c-e4e1-4eda-bb4f-8bcaca0b04ad)

![image](https://github.com/Jusmanov/mandelbrot-set/assets/85308633/ddf9f5f5-8827-4a37-b7d2-4f2b66c9282e)

![image](https://github.com/Jusmanov/mandelbrot-set/assets/85308633/e038b9a2-c4a8-409d-afa1-2100c6d1bc15)


## How to Run:

Test the creation of this model by clicking on the link below. This will bring you to the website, where the Mandelbrot Set is automatically created.

[https://mandelbrot.jusmanov.repl.co/](url)

Mandelbrot Set as shown from the site:

![image](https://github.com/Jusmanov/mandelbrot-set/assets/85308633/36613015-0773-401c-aae0-9fbf59182689)


## **The Mandelbrot Set further explained by OpenAI's ChatGPT:**

### **The algorithm to generate the Mandelbrot Set can be summarized as follows:**

1. Define a complex number c for each point in the complex plane. The real part of c represents the x-coordinate, and the imaginary part represents the y-coordinate of the point.

2. Initialize z as 0, representing the iterative sequence.

3. For each point c, perform a fixed number of iterations (MAX_ITERATIONS) or until the magnitude of z exceeds a predetermined threshold (e.g., 2). In each iteration:

  a. Square z (i.e., z = z^2).

  b. Add c to z (i.e., z = z + c).

4. After the iterations, if the magnitude of z exceeds the threshold, the point is considered to be outside the Mandelbrot Set. Otherwise, it is considered to be inside the set.

5. Repeat this process for each point in the complex plane to generate the complete Mandelbrot Set.

### **Visualization**
The generated Mandelbrot Set is typically visualized using color mapping. Each point is assigned a color based on the number of iterations it took to determine whether it belongs to the set or not. This coloring technique allows for the creation of captivating and visually stunning images.

The Mandelbrot Set exhibits self-similarity, meaning that as you zoom in on any part of the set, you encounter infinitely intricate patterns that resemble the overall shape of the set. It showcases intricate spirals, filaments, and other fascinating structures.

### **Applications**
The Mandelbrot Set has found applications in various fields, including mathematics, physics, computer graphics, and even art. It serves as a rich source of exploration and inspiration for mathematicians, as well as a foundation for studying complex dynamics and fractal geometry.

In computer graphics and visualization, the Mandelbrot Set is a popular subject for generating visually appealing images and animations. Its complex and mesmerizing patterns have captivated artists, mathematicians, and enthusiasts alike, and it continues to be a source of creative inspiration.
