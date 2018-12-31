# SignalPeptides
Predicting signal peptides - Bioinformatics project - KTH 2018

Please download the following files and add them to the folder:
- https://drive.google.com/open?id=1XtMXiV3fnyhrItrEmcm_yo345z8YYrI3
(sizes are too big for github)

To predict other proteomes, run the file newformat.py over the fasta file (change output name in newnumbered.py) and once completed run the file newcontroller.py with the name of the previously generated text file.

You can use the formatinput.py archive to generate the input in the accepted format to test the performance on labeled data. This file requires 4 inputs:
- Folder containing negative samples with tm region
- Folder containing positive samples with tm region
- Folder containing negative samples with non_tm region
- Folder containing positive samples with non_tm region

Bionetwork is the full network. The controller.py archive is an example of usage.
