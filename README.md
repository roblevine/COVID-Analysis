sudo apt install python3-virtualenv
virtualenv jupyter-environment

-OR-

sudo apt install python3.8-venv
python3 -m venv jupyter-environment

create .gitignore with *

sudo apt install python3-pip ipython3
source jupyter-environment/bin/activate
pip install jupyter

jupyter notebook --no-browser


pip install pandas numpy jupyter_datatables plotly

pip install jupyter_contrib_nbextensions
jupyter contrib nbextension install --user
jupyter nbextension enable python-markdown/main

make the notebook trusted!
