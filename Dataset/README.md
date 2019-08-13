
* cullpdb_pc40_res2.0_R0.25_d190801_chains15139 record all the PDB ID and chain ID used during the train and test  
* the data in detaildata are some data recorded used for train and test actually  
pdb_name.txt record the PDB ID and chian ID when extract the positive sample  
pdb_name_noss.txt record the PDB ID and chainID when extract the negative sample  
positive_distance.npy record the atoms' distance matrix of positive sample  
negative_distance.npy record the atoms' distance matrix of negative sample  
positive_ssbond_map.npy record the positive map
negative_nossbonds_map.npy record the negative map
nor_train_shulffle.tfrecords is the data for training  
nor_test_shulffle.tfrecords is the data for testing  
validation.tfrecords is the data for validation  
