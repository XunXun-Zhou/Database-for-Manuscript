# Database for Manuscript Entitled "Rocking Spectrum for Cylindrical Structures Subjected to Bidirectional Pulse-Like Ground Motions"

This is the database for the manuscript entitled "Rocking spectrum for cylindrical structures subjected to bidirectional pulse-like ground motions". All codes in this database were implemented using MATLAB R2023a.

The database contains:

* Trained SVM models employed to develop rocking spectra in the manuscript;
  > ClassificationLearner/SVMmodel.mat
* Data for plotting numerical rocking spectra;
  > SpectraOutput/1.mat
  > ...
  > SpectraOutput/100.mat
* Intensity measures of 100 sets of bidirectional ground motions.
  > IMs.xlsx

An example of plotting rocking spectra is presented in
  > Example_for_Generating_SVMbased_Rocking _Spectra.mlx
