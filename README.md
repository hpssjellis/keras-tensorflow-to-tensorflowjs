# keras-tensorflow-to-tensorflowjs

site at

https://hpssjellis.github.io/keras-tensorflow-to-tensorflowjs/example/model.json



https://hpssjellis.github.io/keras-tensorflow-to-tensorflowjs/example/group1-shard1of1.bin



run the setup.sh

then run kera01.sh 

then run convert-kera-to-tfjs.sh

should put a tfjs saved file in the folder for it.



tensorflowjs_converter \
    --input_format=keras \
    model.h5 \
    tfjs_target_dir
