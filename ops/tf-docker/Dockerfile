FROM jupyter/tensorflow-notebook

RUN conda install --quiet --yes \
    'mlflow=1.0.0' \
    'psycopg2'

RUN pip install --upgrade jupyter_http_over_ws>=0.0.7 && \
  jupyter serverextension enable --py jupyter_http_over_ws

