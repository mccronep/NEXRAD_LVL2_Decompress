Author: Dr. Paul Harasti (NRL)
July 1, 2016

This is code to decompress LDM-compressed NEXRAD level II data.
The links/paths to the LDM libraries need to be active/accessible in
your environment in order to compile the executable
nexradII.exe via the Makefile.

type "make" to make the executable nexradII.exe

To decompress the sample LDM-compressed NEXRAD level II file,
PGUA20160602_055618_V06.compress.raw,
and create the decompressed level II file, PGUA20160602_055618_V06.raw, type 

cat PGUA20160602_055618_V06.compress.raw | ./nexradII.exe PGUA20160602_055618_V06.raw

