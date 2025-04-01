# pd-live

Pure Date patches for Live Electronics

## Repository structure

 The *pd-live* repository acts as a project folder for live electronics environments.

### Main folder

In the main folder you can add the main project and cue lists.
The patcher *main.pd* is a standard environment proposed by the authors.

### controls

The *Controls* folder contains abstractions to control your patch.
> - **l.cue.pd** cue list reader

### DSP_obj

The *DSP_obj* folder contains all signal processing abstractions.
> - **l.play.pd** subpatch to l.player~.pd
> - **l.player~.pd** audio file reader.

### logic

The *logic* folder contains basic abstractions with specific functions needed for other abstractions.
> - **counter.pd** when it receives a bang, counts fom *min* to *max* with a given *pace*.

### sounds

The *sounds* folder collects sounds files.
