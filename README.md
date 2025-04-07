# pd-live

Pure Date patches for Live Electronics

## Repository structure

 The *pd-live* repository acts as a project folder for live electronics environments.

### Main folder

In the main folder you can add the main project and cue lists.
The patcher *main.pd* is a standard environment proposed by the authors.

### data folder

The *data* folder contains abstractions working at control rate speed.
All objects are named *le.obj.pd*.
All subpatchers for

### DSP

The *DSP* folder contains all signal processing abstractions.
All objects are named *le.obj~.pd*.
All subpatchers for DSP abstractions are named *l0.obj.pd*.

### utility

The *utility* folder contains basic abstractions with specific tasks.
All objects are named *u.obj.pd*.

### sounds

The *sounds* folder collects sounds files.
