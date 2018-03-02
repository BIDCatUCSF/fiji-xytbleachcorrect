// Name:
//	wideguy_xyt_bleachcorrect_Imaris_v2.txt
//
// Description:
//	fiji macro for performing xyt Bleach Correction using the histogram 
//	matching method:
//
//	https://imagej.net/Bleach_Correction
//
//	and file conversion to be opened in Imaris. Inspired by BIDC's 
//	wideguy microscope, Ed Roberts and Kelly Kersten
//
// Usage:
//	0) Create a folder for input images and one for resultant output images
//	1) Open your image stack in FIJI
//	2) In FIJI: 
//		Plugins -> Macros -> Run...
//		and select the text file named wideguy_xyt_bleachcorrect_Imaris.txt 
//	3) Choose the input folder
//	4) Choose the output folder
//	5) From the popup window select which channels you wish to perform the bleach correction
//	5) Grab coffee
// 
// Output:
//	.ics and .ids file for each image stack
//	
//	to open the output in Imaris, drag the .ics file into Imaris' Surpass 
//
// Author:
//	Adam Fries 2018.02.21
//
// Details:
//	Intended only for use of 2-channel time-series from uManager output files
// 	Does not work for z-stacks...yet
// 
// Dependencies:
//	FIJI BleachCorrection plugin
//	FIJI BioFormats
 