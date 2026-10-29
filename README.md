MBA660 User Guide：

The Multi-modal Brain Atlas with 660 cortical and subcortical regions of interest (MBA660) is provided by the College of Intelligence Science and Technology, National University of Defense Technology. This atlas includes 552 cortical subregions, 74 subcortical subregions, and 34 cerebellar subregions, which were parcellated with a sample adaptive localized simple multiple kernel K-means algorithm (X. Liu et al., IEEE T-PAMI, 2025).

How to use the MBA660：

1) Copy the 4 files in your SPM12/atlas directory:  
unix> mkdir /usr/local/soft/spm12/atlas 
unix> cp ./MBA660.nii /usr/local/soft/spm12/atlas 
unix> cp ./MBA660.xml /usr/local/soft/spm12/atlas  
unix> cp ./MBA660_1mm.nii /usr/local/soft/spm12/atlas  
unix> cp ./MBA660_1mm.xml /usr/local/soft/spm12/atlas  
2) Launch Matlab unix> matlab
3) Using spm Atlas labelling function : “ spm (Results-Atlas)” 
3.1) Launch spm from the command window >> spm fmri 
3.2) Select the desired contrast, mask, probability and extent threshold in the regular “Results”. In the SPM12 Results window: Atlas / Label using / MBA660 (You may in the SPM Graphics window need to right click on the sections, and select Display > Labels > MBA660). 
3.3) Then you get the label with a right click on the coordinates in the Graphic window.

Reference:

X. Liu et al., "Sample Adaptive Localized Simple Multiple Kernel K-Means and its Application in Parcellation of Human Cerebral Cortex," in IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 47, no. 9, pp. 8134-8147, Sept. 2025, doi: 10.1109/TPAMI.2025.3573613.
