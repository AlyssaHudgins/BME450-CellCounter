# Title
  "BME450-CellCounter for Phone Applications"

## Team members
  Ari Aghevli and Alyssa Hudgins

## Project description

  Dataset: 

  Goal: Create a low-cost solution to live and dead cell counting using deep learning

  For researchers who do cell culture routinely, counting cells is a key metric by which to determine the health of their cultures, and how many cells they should seed into a new flask when passaging. While live cell counters do exist, such as the Logos LUNA-FL [1]  and NucleoCounter® [2], they are often very expensive, reaching prices in the 1000s. This price point is not achievable for all research labs, especially ones that do not have excess funding. These pieces of equipment can also be costly to maintain and repair, leading to many labs opting to do research without them. While traditionally cells can be counted with a hemocytometer and clicker, this process is time-consuming and can require scientists to count hundreds of cells, depending on the confluency of the culture.
The goal of our project is to count cells using a machine-learning algorithm, that could eventually be incorporated into a phone or computer application. Microscope images can be projected onto larger monitors with the use of an adapter, which typically retail for around 300 USD - much less than the thousands of dollars a cell counter may cost. Magnification (via the projector) would need to be conducted to increase the field of vision of the hemocytometer. By using these images to count cells, there is the possibility to save research labs money on equipment.
To implement this project, we will be using the Broad Institute's free cell image datasets. They have a variety of different cell types imaged, all with numerous pictures in each folder. This will allow us to train the model on many different types of cells.

The biggest issue with this project will be ensuring that the model can accurately define cell boundaries and recognize cells of different shapes and sizes. Historically, cell models have also had issues with counting the individual number of cells when cells are clustered together. Given these challenges, there are many opportunities to improve on the existing cell counting technology. By using the large data sets provided by the Broad Institute, we hope to improve the field and provide a less cost-prohibitive solution to cell counting.
  
