# fixdisulphide

## This is a stub directory for something I need to write!

Fix two cys sidechains that are close enough to form a disulphide into
the correct conformation

The files in `testdata` demonstrate the problem:

- `4ma3.pdb` is a structure that has a disulphide between residues L94
  and L95D
- `4ma3_mod.pdb` is a model that has the cys sidechains pointing in
  the wrong direction.

This code will move those sidechains such that EM would sort out the
conformation.

