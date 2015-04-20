# Learn How To Print in 3D

This is a workshop we hold at Solid State Depot.  It is an introductory hands-on tutorial covering how to use a 3D printer.

The curriculum for this workshop has evolved over time.  It originally started as a demonstration.  It eventually covered the software toolchain in depth and included operation of a 3D printer while topics were covered lecture style.

The workshop is now a hands-on workshop where students are given their own 3D printer to use (sometimes they share).  We have enough 3D printers at SSD to support groups up to 12 at a time in this manner.

The goal of the workshop is to train users how to print something on a SSD 3D printer.  We start by covering what not to do.  Then we perform inspections, connect to the printer, and finally manufacture our 3D printed object.  We print an "SSD Certified" emblem designed in OpenSCAD using our 3D printer software toolchain.

The author has been providing this workshop for over 2 years.  Anything can go wrong with a 3D printer at anytime.  If you are just getting started providing instruction then you should consider starting with very small groups of 2 or 3 and practice for larger groups.

This is an S5 presentation.  There is a printer-friendly version.

OOPS!  There are _important_ Notes but they only appear in the text-only version.  That is a bug w/S5.

## Demo Parts and GCode
There are a growing number of parts that provide samples of how different parameters change the GCode output.  They are zipped in lets_slice/lets_slice.zip.  Extract this file to use them.  The GCode files are in lets_slice/gcode (unzipped).  Actually, there are subfolders that contain the GCode - the names of these folders correspond to the version of GCode that generated the file.  Each subfolder should have an Open Office Spreadsheet (.ODS file) with a legend for _each_ GCode file.

## Contribute
If you want to contribute more parts and/or sample GCode files, please follow these guidelines:
+ Follow the naming convention for GCode folders, i.e. version of Slic3r.
+ Use a very verbose name for the GCode file, as has been attempted.
+ Update or create a new Open Office Spreadsheet legend file with a better description of the parameters used for the GCode.  Even verbose names will be forgotten.

-Free