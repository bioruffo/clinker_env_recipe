Working recipe for a conda env for Clinker dependencies. Includes python 2.7, samtools, STAR, R and the gviz and biomart R libraries.  
(clinker is: https://github.com/Oshlack/Clinker)

Usage:  
```
git clone https://github.com/bioruffo/clinker_env_recipe
cd clinker_env_recipe
conda env create -f clinker.yaml
```

And of course you'll want to  
`git clone https://github.com/Oshlack/Clinker` 
