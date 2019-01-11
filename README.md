# *Free Music Alternative Playlists*
# Abstract
It can be tough to know what we would like to listen when faced with an archive of thousand of musics. For our project we wondered how we could automatically generate a list of songs that would correspond to one's taste using the [Free Music Archive avalaible](http://freemusicarchive.org/) on the internet.


# Dataset
Since the dataset is quite large, to use these scripts you have to download the following
data: [fma_metadata.zip](https://os.unil.cloud.switch.ch/fma/fma_metadata.zip) (342 MiB).
Extract the content of `fma_metadata` folder into the `data` folder.

# Usage
- Generate the corresponding small FMA dataset graph by running `Graph creator.ipynb` 
- Put your music in the `audio` folder, you can add as many songs as you wish, each subfolder
corresponds to one desired playlist. Two Demos folder are included as examples.
- Run `Extractor.ipynb` to extract the features of each of your songs. (It will take some time)
- Finally, open `Playlist creator.ipynb`. Modify the parameters as you like.

# Troubleshooting
- You may want to use the provided `environment.yml` conda environment to execute all the scripts properly
- If you have any trouble with `Extractor.ipynb`, an already extracted demos songs features are avalaible in the `data` folder, you can simply run `Playlist creator.ipynb`

# Reference
**FMA: A Dataset For Music Analysis**: Michaël Defferrard, Kirell Benzi, Pierre Vandergheynst, Xavier Bresson, 2017.  
[GitHub](https://github.com/mdeff/fma). [paper](https://arxiv.org/pdf/1612.01840.pdf).

# EPFL NTDS students
* Team: `30`
* Students: `Joachim Tapparel, Tim Tuuva, Lucas Biotto, Anael Buchegger`
* Dataset: `Free Music Archive`
