==============================
M01_V0000_04WM_ExampleAltBoth
==============================

keb 2016-09-29

This model is used as an Alternative to compare results to the Base model.
It combines options from M01_V0000_02WM_ExampleAltBridge and M01_V0000_03WM_ExampleAltBarrier

Copied from M01_V0000_01WM_ExampleBase, with the following changes:
	Tamiami Trail bridge was implemented by changing culverts 56, 57, and 58 to 'no flow', and adding one-mile weir to canal 'culvert57' called 'TTbridge5mi'.
	L31N seepage barrier was implemented by increasing up-down length of cells in miami oolite and setting them to inactive cells. These changes are seen in the Oolite 'lower level' file and in the addition of an internal boundary condition to the Miami Oolite layer.


