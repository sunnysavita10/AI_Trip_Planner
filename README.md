# AI Trip Planner App with LLMOps using LangGraph framework

# Project setup instructions
## 1. Checking for ```uv``` package manager package
To check whether the **uv** package manager is installed, open command prompt or terminal and type the following and hit ```Enter.``` 
```bash
uv --version
```
If installed, it should give an output of the version. Alternately, in your virtual environment, run the following Python code to check for the presence of uv executable script.

```python
import shutil
print(shutil.which("uv"))
```
## 2. Installing ```uv```
```bash
pip install uv
```
- Test to see if uv installation is working correctly. This globally installs pandas library.
```bash
uv add pandas
```

## 3. Create and initialize working directory. 
This will create the basic project structure.
```bash
uv init AI_Travel_Planner
```
## 4. Check for Python libraries available on your local pc 
```bash
uv pip list
```
## 5. Check Python versions available on your local PC and download relevant ones if necessary

Run in terminal. This prints the total available versions
```bash
uv python list
```
-> Global install PyPy for a superfast JIT Python interpreter. This is 3x faster than CPython and is beneficial if you're running CPU-bound tasks and low-memory PCs.
```bash
uv python install pypy-3.10.16-windows-x86_64-none
```

#if you have conda environment activated then deactivate that
```bash
conda deactivate
```
-> Conda support for PyPy is not available for Python>=3.10, so you can use CPython instead as an alternative.

Run below code from in your workspace to create virtual environment and to locally download and use CPython 3.10.18
```bash
uv venv env --python cpython-3.10.18-windows-x86_64-none
```

```bash
uv venv env --python cpython-3.10.18-windows-x86_64-none
```

## use this command from your workspace to activate the virtual env
```bash
C:\Users\sunny\AI_Trip_Planner\env\Scripts\activate.bat
```


