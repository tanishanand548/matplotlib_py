# matplotlib_py

A beginner-friendly guide to data visualization using **Matplotlib** and **Pandas** in Python.

## 📚 Overview

This repository contains a Jupyter notebook (`matplotlib.ipynb`) that demonstrates various plotting techniques and visualization methods using the Matplotlib library, integrated with Pandas DataFrames.

## 📊 Contents

The notebook covers the following topics:

- **Basic Line Plot** - Simple x-y plotting
- **Customized Line Plot** - Colors, markers, line styles, and widths
- **Multiple Line Plots** - Comparing Year-over-Year (YoY) data
- **Bar Charts** - Displaying categorical data
- **Histograms** - Distribution visualization
- **Pie Charts** - Proportional data representation
- **Scatter Plots** - Relationship visualization
- **Subplots** - Multiple plots in a single figure
- **Pandas Integration** - Creating plots from DataFrames
- **Saving Plots** - Exporting visualizations as images

## 🚀 Getting Started

### Prerequisites

- Python 3.12.1 or higher
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository:
```bash
git clone https://github.com/tanishanand548/matplotlib_py.git
cd matplotlib_py
```

2. Install required packages:
```bash
pip install matplotlib pandas numpy
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Open `matplotlib.ipynb` and run the cells to explore different visualization techniques.

## 📦 Dependencies

- **matplotlib** (3.10.9) - Data visualization library
- **pandas** (3.0.3) - Data manipulation and analysis
- **numpy** (2.4.5) - Numerical computing

## 💡 Example Usage

```python
import matplotlib.pyplot as plt
import pandas as pd

# Create sample data
x = [1, 2, 3, 4, 5]
y = [10, 12, 15, 13, 25]

# Create and customize plot
plt.plot(x, y, color='green', marker='o', linestyle='dashed', linewidth=2)
plt.title("Sample Plot")
plt.xlabel("x-axis")
plt.ylabel("y-axis")
plt.show()
```

## 🎯 Key Features Demonstrated

✅ Various chart types (line, bar, histogram, pie, scatter)  
✅ Plot customization (colors, markers, styles)  
✅ Multi-plot layouts with subplots  
✅ Integration with Pandas DataFrames  
✅ Saving plots as image files  

## 📝 License

This project is open source and available for educational purposes.

## 🤝 Contributing

Feel free to fork, modify, and improve this repository. Contributions are welcome!

---

**Happy Plotting! 📈**
