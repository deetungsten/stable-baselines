# stable-baselines-tf2 (installable version)
The original [stable-baselines](https://github.com/hill-a/stable-baselines) repo only supports TF1.x.

The sophiagu [stable-baselines-tf2](https://github.com/sophiagu/stable-baselines-tf2) deletes and changes the existing stable-baseline library

This repo merges the two together so that you can install it via one line using pip which simplifies for usage like Google Colab


## Installation Instruction
- Run the follow command
```
python3 -m pip install git+git://github.com/deetungsten/stable-baselines.git
```
- Remove this version of stable-baseline-tf2
```
python3 -m pip uninstall git+git://github.com/deetungsten/stable-baselines.git
```

## Notes (as per sophiagu's version)
- This repo does not work with `tensorboard` yet due to some weird compatibility issues for `tf.summary` in TF1.
