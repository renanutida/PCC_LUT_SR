# PCC_LUT_SR
Fractional look-up table based super resolution for point clouds coded with octree on TMC13 (MPEG-GPCC).

This is a super resolution solution for post-processing decoded point clouds, whose geometry has been encoded with octree under TMC13. To run, use the following line: 

sr_lut_frac_core(FILE_NAME, RATE, PATH_TO_PLY_FILE);

Please, refer to file run_SR.sh as an example. The user must set-up the correct folders and input parameters. 

If you use this project, please cite the following:

https://www.techrxiv.org/articles/preprint/Point_Cloud_Reconstruction_From_Truncated_Geometry-Based_Streams/14720991
https://www.techrxiv.org/articles/preprint/Fractional_Super-Resolution_of_Voxelized_Point_Clouds/15032052/1
