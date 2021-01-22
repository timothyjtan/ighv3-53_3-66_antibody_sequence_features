# Rosetta modeling of G100Y mutation in CC12.1

## Dependencies

* [Rosetta Software Suite](https://www.rosettacommons.org/software/license-and-download)

## Steps

1. To generate 100 poses, run `<rosetta_location>/main/source/bin/fixbb.static.macosclangrelease -s CC12_1.pdb -resfile CC12_1_G100Y.resfile -nstruct 100 -out:prefix CC12_1_G100Y_ -out:path:all <output_folder>` while in the folder where **`CC12_1.pdb`** is located.
    * Change `macosclangrelease` depending on your operating system.

## Notes

* The parameter _nstruct_ can be varied depending on the number of output poses. In our case, we chose 100 output poses. These poses are in the zipped file **`output_files_CC12_1_G100Y.zip`**.
* Scores are enclosed in the zipped file **`output_files_CC12_1_G100Y.zip`**. The best (lowest) scoring pose is **`CC12_1_G100Y_0087.pdb`**.