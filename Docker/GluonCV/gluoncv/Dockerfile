# Install GluonCV
# https://cv.gluon.ai/install.html

# Install Jupyter to toy with GluonCV
FROM jupyter/datascience-notebook:notebook-6.1.4

# https://pypi.org/project/opencv-python/
RUN pip3 install opencv-contrib-python

# https://cv.gluon.ai/install.html
RUN pip3 install --upgrade mxnet gluoncv

RUN mkdir -p gluoncv/py_examples/

COPY /py_examples/ gluoncv/py_examples/
