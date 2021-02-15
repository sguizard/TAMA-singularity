# TAMA-singularity
A definition file for building TAMA singularity container

## Building container
```
sudo singularity build TAMA.{sif, def}
```

## Using TAMA
There are two main Python scripts in TAMA: 
* tama_collapse.py 
* tama_merge.py

They can be run as follows:

### [tama_collapse.py](https://github.com/GenomeRIK/tama/wiki/Tama-Collapse)
```
singularity exec TAMA.sif tama_collapse.py -h
```

### [tama_merge.py](https://github.com/GenomeRIK/tama/wiki/Tama-Merge)
```
singularity exec TAMA.sif tama_merge.py -h
```

