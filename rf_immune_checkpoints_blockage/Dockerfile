FROM jupyter/minimal-notebook

RUN pip install onnxruntime pandas openpyxl
COPY forest16.onnx ./forest16.onnx

USER root
RUN chmod 777 /home/$NB_USER/ -R
