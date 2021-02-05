1. Install PyTorch https://pytorch.org/get-started/locally/

   Make sure that the CUDA version is same as your computer.

   Use`nvcc --version`to check your CUDA version.

2. Install apex according to this link: https://github.com/nvidia/apex

3. pip install `fast_bert`

4. Change the route of the folder.

   ```Python
   *DATA_PATH* = Path('/home/mist/Test/Bert/data/')
   *LABEL_PATH* = Path('/home/mist/Test/Bert/labels/')
   *AUG_DATA_PATH* = Path('/home/mist/Test/Bert/data/data_augmentation/')
   *MODEL_PATH*=Path('/home/mist/Test/Bert/models/')
   *LOG_PATH*=Path('/home/mist/Test/Bert/logs/')
   ```

5. Run the code

