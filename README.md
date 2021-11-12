# MusicGenerationModels

All Models are trained with PyTorch version 1.4

To use the generative model (computer_games_generation) follow instructions from [Performance RNN - PyTorch](https://github.com/djosix/Performance-RNN-PyTorch). In addition 
all three prediction models recive the same input as well. 

For all computer_games_generation models valence/arousal and bias/binary, the generation function should be injected with the relvant values. For example:

    ```shell
    python3 generate.py -s saved_models_dir/model.sess -c midi_repo/processed/some/processed.data -bb bias_or_binary_value -va valence_or_arousal_value
    ```
  


