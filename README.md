# Mitochondrial_Project

*This project is composed of 2 main parts: * <return>
  1)The filtering of genetic sequences in our database to find the BEST sequence for each taxa <return>
      ·This was achieved through a python code---I named it "best_sequence.py" <return>
      ·The sample fasta file I used for experimenting my code is named "multispecies.fasta" <return>
  2)The visualization of the mitochondrial genome <return>
      ·All the files used to get the final product are included in the folder named "Mito_Visualization" <return>
      

**best_sequence.py** <return>
-The best sequence is determined by the longest sequence length <return>
-IUPAC codes (the characters we use for ambiguous bases that cannot be determined when the DNA is sequenced) are taken into consideration when calculating the best sequence <return>
  ·Original sequence length - IUPAC count = optimal sequence <return>
  
**Mito_Visualization** <return>
-The .csv files, which contain important info about the squamata and decapoda genomes (the ones we are focusing on) such as gene positions and lengths, are included in the html code in order to get the accurate representation of the genomes <return>
-index.html is the actual code needed to get the donut chart ← we chose donut chart to be the form of our visualizaations <return>
-howtorun.txt gives the instruction on how to run the code mentioned above ← this should be done in terminal 


