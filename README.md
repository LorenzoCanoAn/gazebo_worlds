## Usage
To use the models, the `models` directory needs to be added to the `GAZEBO_MODEL_PATH` environment variable. To do so, add the following line to the end of `~/.bashrc`:
```
export GAZEBO_MODEL_PATH=$GAZEBO_MODEL_PATH:<path to this repo>/models
```
It is also possible to add model path in the Gazebo Client GUI.

Adding `worlds` directory to the `GAZEBO_RESOURCE_PATH` environment variable allows you to specify the world without absolute path. To do so, add the following line to `~/.bashrc`:
```
export GAZEBO_RESOURCE_PATH=$GAZEBO_RESOURCE_PATH:<path to this repo>/worlds
```

