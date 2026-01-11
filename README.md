# LibTutorial
Learn various commonly used Python libraries encountered in research work

## 📚 Tutorials Content（Libraries & Paths）

- NumPy — `tutorials/numpy/`
- Pandas — `tutorials/pandas/`
- Matplotlib — `tutorials/matplotlib/`
- Seaborn — `tutorials/seaborn/`
- PyTorch — `tutorials/pytorch/`
- JAX — `tutorials/jax/`

## Environment Settings
## ⚙️ Environment Settings

This tutorial is organized in **📓 Jupyter Notebook** format and focuses on hands-on API usage for each library.  
To minimize **⚠️ dependency conflicts**, we **strongly recommend** creating an **isolated virtual environment per library**, inside its corresponding tutorial folder.

Unless otherwise specified, all notebooks are written and tested with **🐍 Python 3.12**.

---

### 📁 Recommended Folder Layout

Each library has its own directory and its own virtual environment:

- `tutorials/<libname>/` — 📓 notebooks and resources  
- `tutorials/<libname>/[libname]/` — 🧪 virtual environment for that library  

Example:

- `tutorials/numpy/`
  - `01_basics.ipynb`
  - `[libname]/`

---

### 🧪 Create a Virtual Environment (Python 3.12)

Run the following commands **inside the target library folder**:

```bash
cd tutorials/<libname>
python3.12 -m venv [libname]
```
## 🤝 Contributing

If you are interested in this project and would like to contribute long-term, feel free to contact me at **📧 linzepeng697@gmail.com**.  
For short-term contributions, you are also welcome to submit a **✅ Pull Request (PR)** anytime!









