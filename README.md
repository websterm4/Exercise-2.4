Exercise-2.4
============

#AugustJuliandays = 214 to 244

import glob

filename = 'files/data/modis_files.txt'
#file defined
fp = open(filename,"r")
#open file
sdata = fp.readlines()
#readlines
print sdata[0].split('/')
#split first line to show individual units of the string

file_list = glob.glob("file/data/modis_files.txt")

