# About
Autoversion updates a version comment in your source files

it checks source files by looking for a 'version-line' comment, pulls the checksum out of it, checksums the rest of the file and compares them  
if they don't match, it updates the date, bumps the last digit of the version field in the 'version-line' and updates the checksum
