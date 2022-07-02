Run a command something like this.

python3 run_pretrained_openfold.py \
example_files/fasta_dir \
dummy_database \
--output_dir example_files/results_openfold \
--uniref90_database_path dummy_database/dummy_fas.fas \
--mgnify_database_path dummy_database/dummy_fas.fas \
--pdb70_database_path dummy_database/dummydb \
--uniclust30_database_path dummy_database/dummydb \
--bfd_database_path dummy_database/dummydb \
--model_device "cuda:0" \
--jackhmmer_binary_path jackhmmer \
--hhblits_binary_path hhblits \
--hhsearch_binary_path hhsearch \
--kalign_binary_path kalign \
--config_preset "model_1_ptm" \
--openfold_checkpoint_path <path to the downloaded param>

