# dna_seq

The distinction between pathogenic bacteria and nonpathogenic bacteria is essential within modern medicine for treating infections, diagnosing diseases, and tracing disease outbreaks. More importantly, as nearly 99% of bacteria remains undiscovered, defining characteristics of pathogenic bacteria can help in identifying novel or undiscovered harmful bacteria as well as bacteria that could potentially be used towards drug development. The traditional methods of bacterial identification, such as culturing and biochemical testing, can be time-consuming and expensive. Therefore, my study proposes the use of the BERT language model to identify novel pathogenic bacteria based on their 16S rRNA sequences. The BERT model was found to be cost-effective and efficient, achieving an accuracy of 87%. The approach outlined in this study has the potential to improve the speed, accuracy, and cost-effectiveness of bacterial identification and could be used to identify undiscovered harmful bacteria or bacteria that could potentially be used in drug development.

Within the repository, code is contained for creating the initial BERT model for reading genetic sequences, and then a fine-tuned model for classifying sequences based on pathogeniticy. 
Vocabulary sets, along with data (pathogenic and nonpathogenic bacteria) is outlined as well.
Finally, the model can be found in "dnaBerTo", managing sequence lengths of 1200-1500. 
