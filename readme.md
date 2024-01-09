# Metagenomics service apptainer setup and execution 
```sudo apptainer build organism_query metag_v1.def```

Setting limit for container to run
```ulimit -n 20000```


```singularity shell --bind /tmp/.X11-unix:/tmp/.X11-unix --bind /:/mnt --env DISPLAY=$DISPLAY organism_query.sif```