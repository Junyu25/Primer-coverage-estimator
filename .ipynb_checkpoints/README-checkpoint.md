# Primer-coverage-estimator
This can estimate the primer coverage of 16S&amp;23S

## Primer coverage estimator

### Environment 


```bash
conda actiavte /home/junyuchen/Biosoft/anaconda3/envs/py2
```

Or `conda install primerprospector`

### WorkFlow

#### Split the SILVA DataBase base on domain

`python Split_fasta_base_on_domain.py input_fasta`

#### Primer-coverage-estimator

`python Primer-coverage-estimator.py`

