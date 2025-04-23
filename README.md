# magetbrain-nextflow-nippopy

### a note about params

Parameters are applied in the following order (from lowest to highest priority):

    Parameters defined in pipeline scripts (e.g. main.nf)

    Parameters defined in config files

    Parameters specified in a params file (-params-file)

    Parameters specified on the command line (--something value)

