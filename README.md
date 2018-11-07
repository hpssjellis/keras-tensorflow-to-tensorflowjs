# keras-tensorflow-to-tensorflowjs

site at

https://hpssjellis.github.io/keras-tensorflow-to-tensorflowjs/example/model.json



run the setup.sh

then run kera01.sh 

then run convert-kera-to-tfjs.sh

should put a tfjs saved file in the folder for it.



tensorflowjs_converter \
    --input_format=keras \
    model.h5 \
    tfjs_target_dir
