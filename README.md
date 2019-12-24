# rna_seq_fusion

###############your should do copy four files:################

cromwell-35.jar
Eric_gene_fusion.wdl
Eric_gene_fusion.inputs.json
reference.conf

##############and then:#######################################
 configure Eric_gene_fusion.inputs.json and reference (Number of parallel tasks)

################final Run:####################################
nohup java  -Dconfig.file=reference.conf -jar cromwell-35.jar run Eric_gene_fusion.wdl  --inputs Eric_gene_fusion.inputs.json 2>err &
