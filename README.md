# No-Loose-Ends


### Writhe_Knot_Sampling
An exploration into how different sampling methods of the protein backbone (ie. all positions, every 4, random n, etc..) impact the writhe metric.


### Energy_From_Writhe
10,000 _new_ random CA backbone conformations generated from Lysosome using Carbonara (secondary sections of linker resampled only with conformations having reasonable overlap + writhe due to constraints), full atomistic structure inferred using MODELLER and potential energy of protein estimated with OpenMM. 


Taking the writhe metric from the MODELLER reconstructions of CA, can the potential energy be predicted?