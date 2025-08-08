# Self Driving Cars – Motion Planning

This repository contains experiments and assignments related to self-driving car technologies, focusing on **motion planning** and **mapping**.

## 📄 Project: Occupancy Map Generation

The included Jupyter Notebook (`Motion_Planning/Occupancy_map_generation.ipynb`) demonstrates:

- Simulating a robot in a 2D grid environment.

- Using a LiDAR-based **inverse measurement model** to estimate cell occupancy.
- Updating a probabilistic occupancy grid map with the **log-odds** method.
- Visualizing:
  - The **true map** with robot trajectory.
  ![True Map Demo](assets/videos/true_map.gif)
  - The **inverse model** probability map.
  ![Inverse Model Demo](assets/videos/inverse_probability_model.gif)
  - The **belief map** as the robot explores.
   ![Belief Map Demo](assets/videos/belief_map.gif)
