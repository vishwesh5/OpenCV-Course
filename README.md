# OpenCV-Course
OpenCV Course

conda env create -f environment.yml

nbgrader extension install

nbgrader extension activate

jupyter nbextension install --sys-prefix --py nbgrader --overwrite
jupyter nbextension enable --sys-prefix --py nbgrader
jupyter serverextension enable --sys-prefix --py nbgrader

