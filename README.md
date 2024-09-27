# Genetic_3D_TSP

**Genetic-3D-TSP** is a Genetic Algorithm-based solution for the 3D Traveling Salesman Problem (3D TSP), which could handle large-scale cities in a short time. For large-scale datasets, the project XXXXXXXXXX<!--employs a divide-and-conquer strategy by partitioning the extensive city set into manageable subsets, optimizing each subset's path -->using a Genetic Algorithm, and then efficiently XXXXXXXXXXX<!--connecting the sub-paths using a greedy linking method to form an overall optimal route-->. For some medium or small amount cities, the project XXXXXXX <!--add two-opt and swap optimize to build a better childrens-->.

This program based on course CSCI 561 homework1, so some of the code and algorithm(like time scale) is specifically optimize for the course reequirments. And for course rule, the code cannot be upload until it is finished grading.

## Features
<!--
- **Large-Scale Handling**: Efficiently processes 3D TSP instances with over 1000 cities.
- **Genetic Algorithm Optimization**: Implements selection, crossover, mutation, and other genetic operations to enhance path quality.
- **Divide-and-Conquer Strategy**: Reduces computational complexity by splitting the problem into smaller blocks.
- **Scalability**: Clear and modular code structure allows for easy optimization and extension.
-->.
## Installation and Usage

1. **Clone the Repository**
    ```bash
    git clone https://github.com/benzyfan/Genetic-3D-TSP.git
    cd Genetic-3D-TSP
    ```

2. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3. **Prepare Input Data**
    - The input file `input.txt` should be formatted as follows:
      ```
      n
      x1 y1 z1
      x2 y2 z2
      ...
      xn yn zn
      ```
      - `n`: Number of cities.
      - `x`, `y`, `z`: Coordinates of each city.

4. **Run the Algorithm**
    ```bash
    python history5.py
    ```

5. **View Output Results**
    - The output file `output.txt` will contain:
      - Total distance of the optimal path.
      - Sequence of cities in the path.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, please open an issue
