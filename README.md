# SnapVector
windows apps that opens SnapGene Viewer files, sequencing results, and fasta files and import to VectorNTI database in demo mode.

First working version that will do the expected job, but will not handle unexpected errors.

Opens SnapGene Viewer file, fasta file, and .seq files.

Create .ma4 file and open in VectorNTI automatically.

Include .tq file that need to copy to C:\Program Files (x86)\Invitrogen\Vector NTI Advance 11\Tools\Menu\Analyses so that you can export your VectorNTI file to SnapGene viewer. Open with SnapGene will carry over your features added in VectorNTI, Export to SnapGene will loose all your feature added in VectorNTI and let SnapGene View to detect all the feature for you. File name will show up in description, simple copy and save and paste.

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
