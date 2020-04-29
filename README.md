# RNA-seq Fusion by Ericscript

##your should do copy four files
1. cromwell-35.jar
2. Eric_gene_fusion.wdl
3. Eric_gene_fusion.inputs.json
4. reference.conf

##and then
1. configure Eric_gene_fusion.inputs.json and reference (Number of parallel tasks)

##final Run
- nohup java  -Dconfig.file=reference.conf -jar cromwell-35.jar run Eric_gene_fusion.wdl  --inputs Eric_gene_fusion.inputs.json 2>err &
