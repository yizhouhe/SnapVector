# SnapVector
SnapGene and VectorNTI is a great software package that allow us to analyse Plamid DNA sequence and make molecular cloning a lot easier, howerever, their price is a little too high. The free trial are fullly fuctional and usible with different limitations. SnapGene Viewer make it difficult to modify your sequence and VectorNTI demo don't let you paste sequence when you create DNA sequences.

SnapGene and VectorNTI have their own unique advantages. SnapGene automatically detect known features of the vector and add them automatically, while VectorNTI can align multiple sequence easily. SnapGene manage plasmid in file based system while VectorNTI use database based system to orgernize plamid. While each system have its own advantage that require different skill to understand it, it will be nice if we can combine these two system into one.

SnapVector is a windows apps that opens SnapGene Viewer files, sequencing results, and fasta files and import to VectorNTI database in demo mode. It also include addon extention to add to your VectorNTI system to allow export your VectorNTI file to SnapGene viewer (This function is totally unnecessary since you can achieve the same goal by simply select all sequence, copy, create new SnapGene file and paste, use if you find it a little easier).

#Features
1. First working version that will do the expected job, but will not handle unexpected errors.
2. Opens SnapGene Viewer file, fasta file, and .seq files.
3. Create .ma4 file and open in VectorNTI automatically.
4. Include .tq file that need to copy to C:\Program Files (x86)\Invitrogen\Vector NTI Advance 11\Tools\Menu\Analyses so that you can export your VectorNTI file to SnapGene viewer. Open with SnapGene will carry over your features added in VectorNTI, Export to SnapGene will loose all your feature added in VectorNTI and let SnapGene View to detect all the feature for you. File name will show up in description, simple copy and save and paste.

#Installation
1. Create Foler named SnapVector in C:\Program Files (x86)\ and copy SnapVector.exe to C:\Program Files (x86)\SnapVector
2. Copy "Export to SnapGene.tq" and "Open with SnapGene.tq" to C:\Program Files (x86)\Invitrogen\Vector NTI Advance 11\Tools\Menu\Analyses

#Import SnapGene Viewer file to VectorNTI
1. Right click on .dna file and select "Open with..."
2. Check "Always use this app to open .dna file"
3. Select "More apps", and then select "Looking for another apps in this PC"
4. Browse to C:\Program Files (x86)\SnapVector and select SnapVector.exe
5. Click OK. SnapVector will read the .dna file and create .ma4 file and open in VectorNTI automatically. 
6. It will ask for the Subset Name you want to put the new sequence into, default will be "SnapGene File", change to the subset name you prefered and click ok, sequence will open automatically.
 
#Import .fasta file to VectorNTI
1. Right click on .fasta file and select "Open with..."
2. Check "Always use this app to open .fasta file"
3. Select "More apps", and then select "Looking for another apps in this PC"
4. Browse to C:\Program Files (x86)\SnapVector and select SnapVector.exe
5. Click OK. SnapVector will read the .fasta file and create .ma4 file and open in VectorNTI automatically. 
6. It will ask for the Subset Name you want to put the new sequence into, default will be "Fasta File", change to the subset name you prefered and click ok, sequence will open automatically.
 
#Import Sequencing file .seq to VectorNTI
1. Right click on .fasta file and select "Open with..."
2. Check "Always use this app to open .seq file"
3. Select "More apps", and then select "Looking for another apps in this PC"
4. Browse to C:\Program Files (x86)\SnapVector and select SnapVector.exe
5. Click OK. SnapVector will read the .seq file and create .ma4 file and open in VectorNTI automatically. 
6. It will ask for the Subset Name you want to put the new sequence into, default will be "Sequencing File", change to the subset name you prefered and click ok, sequence will open automatically.
 
#Export VectorNTI file to SnapGene Viewer
1. Close all opening VectorNTI apps
2. Copy included two .tq file to C:\Program Files (x86)\Invitrogen\Vector NTI Advance 11\Tools\Menu\Analyses
3. Run VectorNTI Exporer, browse to the file you want to export, right click and select "Analyses"
4. Select "Open with SnapGene" will carry over your features added in VectorNTI, select "Export to SnapGene" will loose all your feature added in VectorNTI and let SnapGene View to detect all the feature for you. 
5. File will open in SnapGene Viewer and file name will show up in description, simply select, copy, save, and paste.
