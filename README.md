cat > README.md <<'EOF'
# RL-Gridworld-Value-Iteration

Python implementation of **Gridworld MDP planning**: **value iteration** + **policy iteration / policy evaluation** to compute the optimal value function and policy under different discount factors (γ) and reward settings, with printed value grids and policy arrows.

---

## What’s Included

- **Value Iteration (VI):** Iteratively applies Bellman optimality updates to compute \( V^\* \) and the greedy optimal policy.
- **Policy Iteration (PI):** Alternates between **policy evaluation** and **policy improvement** until convergence.
- **Comparative Runs:** Experiments across different **γ / reward configurations** to observe how optimal values/policies change.
- **Readable Output:** Prints the **value function grid** and **optimal policy** (arrow directions + terminal goal state).

---

## Repository Structure

.
├── Kartikay_Gupta_RL_HW3_Programming.ipynb   # Main notebook (implementation + runs)
├── kartikay_gupta_rl_hw3_programming.py      # Python script version
├── README.md
└── MEDIA/
    ├── RL_HW3_1.png
    ├── RL_HW3_2.png
    ├── RL_HW3_3.png
    ├── RL_HW3_4a.png
    ├── RL_HW3_4c.png
    └── RL_HW3_5.png

---

## How to Run

### Option A: Notebook (recommended)
```bash
pip install numpy
jupyter notebook
```

### Option B: Script
pip install numpy
python kartikay_gupta_rl_hw3_programming.py

### code output
### 
![c](https://github.com/Kartikay77/RL-Gridworld-Value-Iteration/blob/main/MEDIA/RL_HW3_1.png)

### 
![d](https://github.com/Kartikay77/RL-Gridworld-Value-Iteration/blob/main/MEDIA/RL_HW3_2.png)

### 
![e](https://github.com/Kartikay77/RL-Gridworld-Value-Iteration/blob/main/MEDIA/RL_HW3_3.png)

###
![f](https://github.com/Kartikay77/RL-Gridworld-Value-Iteration/blob/main/MEDIA/RL_HW3_4a.png)

###
![g](https://github.com/Kartikay77/RL-Gridworld-Value-Iteration/blob/main/MEDIA/RL_HW3_4c.png)

###
![h](https://github.com/Kartikay77/RL-Gridworld-Value-Iteration/blob/main/MEDIA/RL_HW3_5.png)

cat >> README.md <<'EOF'

---

## One-line summary of each output

- **RL_HW3_1:** Value function + optimal policy for the baseline configuration.
- **RL_HW3_2:** Value function + optimal policy after changing the discount factor (γ) or reward setting (comparison run).
- **RL_HW3_3:** Another configuration showing how values/policy shift under different MDP parameters.
- **RL_HW3_4a:** Experiment variant 4a (planning output: value grid + policy arrows).
- **RL_HW3_4c:** Experiment variant 4c (planning output: value grid + policy arrows).
- **RL_HW3_5:** Final run/configuration output (value function + optimal policy).

---

## Notes
- This homework uses **planning / dynamic programming** (no sampling-based learning).
- Convergence speed and value magnitudes depend heavily on **γ** and the reward setup.

---

## License
For educational use.
EOF
