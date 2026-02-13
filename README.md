# Math 1b Visualization Kit 🚀

Welcome to your shiny new engine for the DTU Math 1b course! This setup fixes all those annoying "Module Not Found" and "Matrix" errors so you can focus on the cool graphs.

## 🛠️ Step 1: The One-Time Setup

Open your **Terminal** (Mac) or **Anaconda Prompt** (Windows). Copy, paste, and hit Enter on these commands one by one. Watch the matrix code fly by.

```bash
conda create -n math1b python=3.10 -y
conda activate math1b
pip install dtumathtools sympy matplotlib jupyter
python -m ipykernel install --user --name=math1b --display-name "Python (math1b)"

```

## 🎮 Step 2: Let's Plot!

1. Type `jupyter notebook` in your terminal.
2. Open your `exercise_5.ipynb` file.
3. **Crucial Step:** Go to the top menu: **Kernel** → **Change Kernel** → **Python (math1b)**.
4. Run your cells!

## ⚠️ The Golden Rule

The plotting tool is a bit picky.

- **Do THIS:** `u = [x, y, z]` (Simple Python List) ✅
- **NOT THIS:** `u = Matrix([x, y, z])` (SymPy Matrix) ❌

**Happy Plotting! 📈**
