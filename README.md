# **Ising Model Simulation using Monte Carlo Method**

This project implements the **2D Ising Model** using the **Metropolis Algorithm** to study phase transitions in statistical mechanics. The simulation is performed on both **square and triangular lattices**. 

- For the **square lattice**, we simulate **both ferromagnetic and antiferromagnetic interactions**.  
- For the **triangular lattice**, we simulate **only the antiferromagnetic interaction**.

---

## **Methodology**
- The **Metropolis algorithm** is used to update spin configurations.
- Simulations are run on:
  - **Square lattice** for both **ferromagnetic** and **antiferromagnetic** interactions.
  - **Triangular lattice** for **antiferromagnetic** interaction only.
- The system follows **periodic boundary conditions**.
- Energy and magnetization are computed at each Monte Carlo step.
- Thermal equilibrium is reached over multiple iterations.

---

## **Files Included**
- `ising.ipynb` → Jupyter Notebook containing the simulation.

---

## **How to Run**
### **Option 1: Jupyter Notebook**  
1. Download the `.ipynb` file.  
2. Open Jupyter Notebook.  
3. Run the cells in order.  

### **Option 2: Google Colab**  
1. Open [Google Colab](https://colab.research.google.com/).  
2. Click **"File" → "Upload Notebook"**.  
3. Select the `.ipynb` file.  
4. Run the cells.  

---

## **Results**
- **Phase transitions** are observed based on temperature variations.
- **Ferromagnetic interactions** (square lattice) lead to spontaneous magnetization at low temperatures.
- **Antiferromagnetic interactions** (both square and triangular lattices) show different ordering patterns.

---

## **Dependencies**
- Matplotlib  
- NumPy  

---

## **License**
This project is open-source and available under the **MIT License**.
