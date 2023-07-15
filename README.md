


vf

# get llvm bitcode file, e.g. darknet.bc.opt

# run instrumented analyzer on the bitcode file and dump the analysis result in json
./bin/rank -stat=false -dfree -saber-pta=ander -dump-file=./results/darknet.json ./bc/darknet.bc.opt

# run the ranker on the json result

# run with ground truth in json file


ofb
./bin/array -stat=false -dump-file=./results/patch.json ./bc/patch.bc.opt
