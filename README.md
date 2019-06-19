# Hybrid_project
Hybrid_project


To convert the gff file of S. uvarum (available at http://www.saccharomycessensustricto.org/cgi-bin/s3.cgi?data=Annotations&version=current) run the script in GFF_GTF_conversion.txt

To obtain the orthologuos promoter regions in of S. cerecisiae and S. uvarum, for each species first run the script create_promoters.py. 
Example:

```bash
python promoters_mod.py Saccharomyces_cerevisiae.R64-1-1.93.gtf Saccharomyces_cerevisiae.R64-1-1.dna.toplevel.fa SC_promoters_1000bp.fasta > SC_promoters_1000bp.bed
```


Then run the script create_orthologous_promoters.py using the bed files created by the previous script.
