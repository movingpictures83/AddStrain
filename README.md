# AddStrain
# Language: Python
# Input: TXT
# Output: TSV
# Tested with: PluMA 1.1, Python 3.6

PluMA plugin to add strain information to an Ensembl lineage.

The plugin takes as input a tab-delimited file of keyword-value pairs:
lineagefile:	Ensembl lineage (TSV)
assemblysummary: TXT table, with strain information

Output lineage file (TSV format) will contain the associated strains
