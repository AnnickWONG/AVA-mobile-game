## 05/11/2020
###  1. applications - fc_layers
      Used for single-3FC case, including a 3FC component and one FC layer.   
      #### Unsolved:
      - line 74-77: difference between Dropout & AlphaDropout, relu & selu?
###  2. applications - con2d_bn
      Convolutional layer + Batch Normalization. Using ReLu as activation.
###  3. inception_block
      Graphic OK.


##06/11/2020
###   1. applications - model_inception_multigap
      Used for extraction of narrow MLSP features.
      Using definited size crop as input.
###   2. applications - model_inceptionresnet_multigap
      Same as the previous model except for the base model.
###   3. applications - model_inception_pooled
      Used for extraction of wide MLSP features.
      Similar to the first model, but can take a various size input.
      Using tf.image.resize_area
###   4. applications - model_inceptionresnet_pooled
###   5. fix the problem of the jupyter in pycharm

