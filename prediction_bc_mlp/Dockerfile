FROM jupyter/minimal-notebook

RUN pip install onnxruntime pandas openpyxl
COPY MLP_model3.onnx ./MLP_model3.onnx

USER root
RUN chmod 777 /home/$NB_USER/ -R
