# Procedural-Flower-Generation-with-L-Systems
Developed a Python application as the final project for the Python for Engineering course at university. This application uses L-Systems to procedurally generate a plant, namely L-Py, and PlantGL libraries to generate 3D models of Vinca major Variegata flower.


<img src="/examples/petals_example.png" alt="Petals Example" width="600">
<img src="/examples/leaf_example.png" alt="Leaf Example" width="600">


## Project Purpose

This project was developed as a final showcase for the Python for Engineering course at Adam Mickiewicz University (Poznan, PL). It serves as a demonstration of the ability to utilize Python engineering tools and libraries to create a highly specialized application.

## Project Showcase
- **Step-by-Step Flower Generation:** Check the gifs to see the step-by-step generation process. Each time, the flower is generated uniquely.

<img src="/examples/1001.gif" alt="First GIF" width="400">  
<img src="/examples/1002.gif" alt="Second GIF" width="400">
<img src="/examples/1003.gif" alt="Third GIF" width="400">


- **Presentation Slides:** Explore the [presentation.pptx](presentation.pptx) to find slides that provide a comparison between the generated flowers and real Vinca major Variegata flowers, along with some interesting statistics.

## Installation

To try this code out, follow these steps:

1. **Install Miniconda:**
   - Download and install Miniconda (a minimal Conda installer) from [https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html) based on your operating system.

2. **Open Anaconda Prompt (Miniconda3):**
   - After installing Miniconda, open the Anaconda Prompt (Miniconda3) tool. This will serve as your command-line interface for managing environments.

3. **Create a Conda Environment:**
   - In the Anaconda Prompt, create a new Conda environment and install L-Py and PlantGL by running the following command:
     ```
     conda create -n myenv openalea.lpy openalea.plantgl -c fredboudon -c conda-forge
     ```

4. **Activate the Environment:**
   - Activate the newly created Conda environment using the following command:
     ```
     conda activate myenv
     ```

5. **Open L-Py Tool:**
   - Launch the L-Py tool by running the following command:
     ```
     lpy
     ```

You are now ready to load the .lpy file provided in repository to generate Vinca major Variegata flowers. Enjoy 


## License

This project is licensed under the [MIT License](LICENSE).
