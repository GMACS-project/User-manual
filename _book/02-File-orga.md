# File organisation {#orga}

Gmacs is controlled by a series of text-based input files. These files can be prepared and edited using a text editor of your choice.

## Input Files

  1. `model.dat`: file containing model dimensions and the data (_required_).
  2. `model.ctl`: file containing set-up for the parameters and options chose (_required_).
  3. `model.prj`: file containing specifications for the reference points and projections (_required_).
  4. `gmacs.dat`: file containing the names of the files specified above and ordered as `.dat`, `.ctl`, `.prj`.
  
## Output Files

  1. `gmacs_in.dat`: New version ('echo') of the data file with annotations. 
  2. `gmacs_in.ctl`: New version ('echo') of the control file with annotations. 
  3. `gmacs_in.prj`: New version ('echo') of the projection file with annotations. 
  4. `gmacs_files_in.dat`: Contains the names of the files that have been read as data file, control file and projection file.
  5. `checkfile.rep`: It is produced during the read-in and calculation stages of a model run. It is useful for debugging
  6. `.rep`: These are standard ADMB output files
  7. `gradient`
