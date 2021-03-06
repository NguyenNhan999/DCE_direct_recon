Matlab scripts for Direct Reconstruction in DCE-MRI
============================================================

(c) *Yi Guo*, *Sajan Goud Lingala*, *Krishna Nayak*, Jul 2016.

[Magnetic Resonance Engineering Laboratory](https://mrel.usc.edu)

**University of Southern California**

Code Structure
--------------
### Demo scripts
**Kt_Vp_SEN_AD_3d.m**
Reconstruction script to demonstrate direct reconstruction from under-sampled k-space in retrospective studies.  
Please download data set at https://drive.google.com/file/d/0B4nLrDuviSiWajFDV1Frc3cxR0k/view?usp=sharing for DCE50_0402.mat and
https://drive.google.com/file/d/0B4nLrDuviSiWcGFPOUV1b2VrZUU/view?usp=sharing for T1_0402.mat

### Functions: 
**conc2Ktrans.m**: 
	Convert contrast concentration to TK parameter maps.  
**conc2sig.m**: 
	Convert contrast concentration to signal (images).  
**genRGA.m**: 
	Generate randomized golden-angle radial sampling pattern.  
**Kt_Vp_SEN.m**: 
	Alternatively reconstruct Ktrans and Vp maps using l-bfgs.  
**Ktrans2conc.m**: 
	Convert Ktrans maps to contrast concentration.  
**sig2conc2.m**: 
	Convert signal (images) to contrast concentration.  
**Ktrans2sig_sen_WT.m**: 
	Cost and gradient calculation for the objective function for Ktrans.  
**Vp2sig_SEN_WT.m**: 
	Cost and gradient calculation for the objective funciton for Vp.  
**SAIF_p.m**: 
	Generate population-averaged AIF.  
