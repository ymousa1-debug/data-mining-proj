# Marvel Hero Network Analysis using Graph Theory

This project models the Marvel hero universe as a network to analyze relationships between characters. By representing heroes as nodes and their interactions as edges, the project applies graph theory techniques to identify influential heroes, uncover community structures, and predict potential future collaborations. This type of analysis is useful because it demonstrates how complex relational data can be understood using network-based methods, which are widely used in social networks, recommendation systems, and real-world data mining applications.

---

## Project Video
https://youtu.be/c8qVG-na4K4
---

## Main Notebook
The main deliverable is:
**main_notebook.ipynb**

---

## Research Questions

- Who are the most influential heroes in the network?
- What community structures exist among heroes?
- Which heroes are likely to collaborate in the future?

---

## Dataset

The dataset used is the **Marvel Hero Network dataset** (`hero-network.csv`), which contains pairs of heroes that have appeared together. Each row represents an interaction between two characters.

### Preprocessing:
- Removed self-loops
- Constructed a graph from edge list format

---

## How to Reproduce

This project was built using **Google Colab**.

Steps:
1. Open `main_notebook.ipynb` in Colab
2. Ensure `hero-network.csv` is accessible
3. Run all cells from top to bottom

Environment:
- See `requirements.txt` for full package list

---

## Key Dependencies

- Python 3.12.13 
- pandas  
- networkx  

(Full dependency list available in `requirements.txt`)

---

## Repository Structure

├── main_notebook.ipynb
├── requirements.txt
├── hero-network.csv
├── README.md
└── checkpoints/
├── checkpoint_1.ipynb
└── checkpoint_2.ipynb
