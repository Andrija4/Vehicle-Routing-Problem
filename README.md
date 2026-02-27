# Vehicle Routing Problem Project

This repository contains a project for solving the **Vehicle Routing Problem (VRP)**, an optimization problem used for planning optimal vehicle routes in logistics and transportation.

---

## Project Description

The Vehicle Routing Problem (VRP) focuses on finding the most efficient routes 3 vehicles to deliver goods or services to multiple customers.

The objective is to minimize total operational costs.

---

## How to Use

### Clone the repository

```bash
git clone https://github.com/Andrija4/Vehicle-Routing-Problem-Project.git
cd Vehicle-Routing-Problem-Project
```

### Install dependencies

Make sure you have **Python 3.x** installed.

If a `requirements.txt` file exists:

```bash
pip install -r requirements.txt
```

If not, check the imported libraries in the source code and install them manually.

### Run the program

Run one of the available algorithms:

```bash
python algoritam01_shortesRoute.py
```

or

```bash
python algoritam01_greedyAdd.py
```

---

## Project Structure

```
Vehicle-Routing-Problem-Project/
│
├── algoritam01_shortesRoute.py   # Shortest Route heuristic
├── algoritam02_greedyAdd.py      # Greedy Add heuristic
└── README.md
```

---

## Example Input

```
5   # Number of customers
```

---

## Future Improvements

- [ ] Add support for additional heuristics
- [ ] Implement advanced optimization algorithms (e.g., Genetic Algorithm, Simulated Annealing)
- [ ] Add visualization of routes
- [ ] Create a graphical user interface (GUI)
- [ ] Improve documentation

---

## Author

Developed by **Andrija4**  
GitHub: https://github.com/Andrija4

Feel free to open an issue or submit a pull request if you'd like to contribute.

---

## License

This project currently does not have a specific license and is provided **"as-is"**.

If you plan to use or modify this project publicly, consider adding a license (e.g., MIT License).
