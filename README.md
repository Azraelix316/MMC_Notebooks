# MMC Notebooks

These notebooks are the code behind many of the topics we discuss during our meetings. Feel free to clone and play around with the specific methods, models, and datasets used.
## 🛠 Prerequisites

Before you can run these notebooks, you'll need to set up your environment. If you've never used Python before, we recommend Option A.
#### Option A: Anaconda

Download and install Anaconda. It is a "bulk" installer that includes Python, Jupyter Notebook, and almost every data science library we use (like NumPy and Pandas) in one go.
#### Option B: The "Light" Way (For existing Python users)

If you already have Python, you can install Jupyter via your terminal:

```bash
pip install notebook
```

## 🚀 How to use these notebooks

Jupyter Notebooks are interactive documents that mix Markdown (text like this) with Code (Python).

Clone the Repository: Open your terminal/command prompt and run:
```Bash

git clone https://github.com/YourClubName/MMC-Notebooks.git
```
(Alternatively, click the green "Code" button at the top of this page and select "Download ZIP")

Launch Jupyter:
Navigate into the folder in your terminal and type:
```Bash

jupyter notebook
```
A tab will automatically open in your web browser showing the file dashboard.

Run Cells:
Click on a .ipynb file to open it. To run a block of code, click the cell and press Shift + Enter.

## 💡 Notes & Tips

The Kernel: If your code isn't running, look at the top right corner. If the circle is solid black, the "Kernel" (the brain running the code) is busy. If it's empty, it's ready!

Don't worry about breaking things: You are working on a local copy. If you mess up a notebook, you can always delete the folder and clone it again.

Markdown vs. Code: You can change a cell type using the dropdown menu in the toolbar. Use Markdown to write notes about what you’re learning!

## ❓ Troubleshooting

"Command not found": If you just installed Anaconda, you may need to restart your terminal/computer for the jupyter command to be recognized.

Missing Libraries: If a cell gives you a ModuleNotFoundError, you can usually fix it by running pip install <module_name> in your terminal.