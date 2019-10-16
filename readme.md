conda environment YAML files    


Initial Install    
```
$ wget https://raw.githubusercontent.com/ericmjl/conda-envs/master/{env_name}.yml -O environment.yml  
$ conda env create -f environment.yml     
$ source activate {env_name}
```
    
Update        
$ wget https://raw.githubusercontent.com/ericmjl/conda-envs/master/{env_name}.yml -O environment.yml
$ conda env update -f environment.yml  # this is where the update magic happens
$ source activate {env_name}

Purpose
