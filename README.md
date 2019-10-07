# scikit-fuzzy-project
Fuzzy Logic Implementation for <put_fuzzy_related_problem_here>

## Getting started
Install requirements in a virtual environment. In this guide, I'll use Conda.
```sh-session
# Exit the current venv
(shiny_new_env)$ conda deactivate

# Spin up a new one
$ conda create -n <your_env_name> python=3.4

# Activate it
$ conda activate <your_env_name>

# Install from our fancy new file
(<your_env_name>)$ pip install --user --requirement requirements.txt

# Run the Jupyter Lab
(<your_env_name>)$ jupyter lab
```

If Jupyter Lab is not using your kernel, add the kernel.
```sh-session
(<your_env_name>)$ jupyter lab ipython kernel install --user --name=<any_name_for_kernel>
```