# strong_wind_axis_python_cuda

## Setup the Environment

```bash
docker run --gpus all -it --rm --net host --name rapids_$USER -v $PWD:$PWD -w $PWD rapidsai/rapidsai:0.14-cuda10.2-base-ubuntu18.04-py3.6 bash
```
## Install/Launch Jupyter Notebook

```bash
conda install jupyterlab
jupyter lab --NotebookApp.token="" --allow-root --ip=0.0.0.0 &
```