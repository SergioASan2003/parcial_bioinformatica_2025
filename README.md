# parcial_bioinformatica_2025
Punto 1
a) use la funcion cat para concatenar las 8 secuencias en un archivo .fasta llamado seqs_concatenadas.fasta
```cat Balaena_mysticetus.fasta Balaenoptera_acutorostrata.fasta Balaenoptera_borealis.fasta Balaenoptera_brydei.fasta Balaenoptera_edeni.fasta Balaenoptera_musculus.fasta Balaenoptera_omurai.fasta Caperea_marginata.fasta Caperea_marginata_2.fasta > seqs_concatenadas.fasta```

b) -En atom pude descomponer la primera linea de cada secuencia de la siguiente forma (>\w+)(.)(\d)(\s)(\w+)(\s)(\w+)(\s)(\w+)(\s)(\w+)(,)(\s)(\w+)(\s)(\w+)
    y reemplazar con $1$2$3_$5_$7 para aquellas lineas a los 6 encabezados a los que les servia y sucesivamente cambiando con expresiones regulares para dejar todas en el formato >AB201258.1_Balaenoptera_edeni
No pude aplicar los cambios con sed
