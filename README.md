# aips-build-dependencies
Mirror for dependencies needed to build AI-Powered Search containers

To create part files:
split -a 1 -b 25m FILENAME FILENAME.part

To merge part files:
cat FILENAME.part* > FILENAME 
