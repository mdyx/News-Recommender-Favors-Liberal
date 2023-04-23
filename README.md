# News-Recommender-Favors-Liberal

Here are data and codes for the paper News Recommender Favors Liberals: Estimating Algorithmic Bias through Causal Inference.

## Prepare the dataset

1. Download the MIND dataset from [https://msnews.github.io/](https://msnews.github.io/).
2. Unzip the files `MINDlarge_train.zip` and `MINDlarge_dev.zip`.
3. Put the folders `MINDlarge_train` and `MINDlarge_dev` into `data/mind`.
4. Run `chmod 777 prepare_data.sh` and `./prepare_data.sh` in `data/mind`.

## Run the codes

1. Run `chmod 777 run.sh` and `./run.sh` in `code` to get the effects used in the paper. For convinience, we have already prepared them in `./code/get_effect/result/mind`.
2. All the figures and results presented in our paper and SI can be reproduced by running `./code/figures.ipynb`. You can cancel comments with `plt.savefig()` and the corresponding figures will be automatedly saved in `./figures`.

Thanks for using our code!
