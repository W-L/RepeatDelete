# RepeatDelete

This script can make a plot of fragments found by RepeatMasker that align to a consensus of a TE
The input is an output file from RepeatMasker, run with `-xm` (the `.out.xm` file is much nicer for parsing!)

An example RepeatMasker command:
`RepeatMasker -pa 4 -s -nolow -norna -div 20 -lib LIBRARY -u -xm ASSEMBLY`

## Parameters 

All parameters and switches to change are at the top of the script.
The repository contains a RepeatMasker file for the TE hobo in the r6.30 assembly from flybase.
