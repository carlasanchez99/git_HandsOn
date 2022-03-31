# git_HandsOn

The seqClass.py script returns the type of sequence (DNA, RNA, none of these or either DNA or RNA) and if there is a specific motif or not.
If the sequence is DNA or RNA, percentages of the nucleotides will be shown. 

Example 1: want t o know if ACTG is DNA or RNA.

seqClass.py -s ACTG

#This sequence is DNA.

#A: 0.25 % 
#C: 0.25 % 
#G: 0.25 % 
#T: 0.25 %


Example 2: want t o know if ACTG is DNA or RNA and if there is TG motif.

seqClass.py -s ACTG -m TG

#The sequence is DNA 

#A: 0.25 % 
#C: 0.25 % 
#G: 0.25 % 
#T: 0.25 %

#Motif search enabled: looking for motif "TG" in sequence "ACTG"... FOUND
