

# Bayesian Search and Rescue

This repository contains a Python-based simulation for a **Bayesian Search and Rescue** scenario. The program models a search for a missing sailor using probabilistic methods to optimize search efforts across multiple areas.

---

## File Description

### `BAYES.py`
- **Description**:
  - The script implements a Bayesian Search and Rescue simulation.
  - It divides the map into three distinct search areas and uses Bayesian probability to guide the search in an optimal way.
  - The program features a probabilistic model, visualization of search areas, and updates probabilities dynamically based on search results.
- **Features**:
  - Simulates the location and rescue of a missing sailor using probabilistic methods.
  - Dynamically updates target probabilities using Bayes' theorem after each search.
  - Allows interactive user input to select search areas.
  - Visualizes the search process on a map with the sailor's actual and last-known positions.
  - Detailed search effectiveness probabilities for each area.
- **Dependencies**:
  - Python libraries: `numpy`, `opencv-python` (`cv2`), `itertools`, `random`, `sys`.
  - A map image file (`images/cape_python.png`) is required to visualize the search areas.
- **How to Run**:
  1. Ensure the required dependencies are installed:
     ```bash
     pip install numpy opencv-python
     ```
  2. Place the map image (`images/cape_python.png`) in the appropriate directory.
  3. Run the script:
     ```bash
     python BAYES.py
     ```
  4. Follow the prompts to select search areas and view the results.

---

## How It Works
1. **Map Initialization**:
   - The map is divided into three predefined search areas.
   - The sailor's actual location is randomly generated within one of the areas.
2. **User Interaction**:
   - The user selects areas to search using a menu-based interface.
   - The script simulates the search process and provides feedback on search results.
3. **Dynamic Probability Updates**:
   - The probabilities for each search area are updated using Bayes' theorem based on the effectiveness of the previous searches.
4. **Visualization**:
   - The map is displayed with search areas and markers for the sailor's last-known and actual positions.

---

## Example Gameplay
1. Start the program and view the map with search areas.
2. Use the menu to select one or more areas to search.
3. The program provides feedback on whether the sailor was found or updates the probabilities for the next search.
4. Continue searching until the sailor is found or all searches are exhausted.

---

## Additional Notes
- This simulation is designed for educational purposes to demonstrate Bayesian search methods.
- The program can be extended or modified to include more search areas or additional features.

---


