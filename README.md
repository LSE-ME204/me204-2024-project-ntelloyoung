# Project MobyGames
Collect information from the the video games on the first Xbox

## Team
* Nicolas Tello
* Cagan Dalman

We worked together to collect data, clean it, and it to create a database. After that, we went our seperate ways

## How to replicate

1. Install Python and a conda distribution (either Anaconda or Miniconda)
2. Create a new conda environment fot his proecjt and activate it

```bash
conda create -n mobygames --python=3.9
condo activate monygames
```

3. Instead the required packages
```bash
pip install -r requirments.txt
```

4. If running on VScode, clone this repository and activate the correct environment every time you are running a notebook

5. Go to the [Moby Games register page](https://www.mobygames.com/user/register/), create an account and add your credentials to the credentials.json file
```json
{
    "username": "<your MobyGames username>",
    "password": "<your MobyGames password>"
}
```
6. Go through each of the notebooks under the 'notebook/' folder, read and run them in order

All analysis is done in [Index.mb](../docs/index.md)

# Generative AI Acknowledgement
Generative AI, specificaly copilot was used throughout this project. The main uses of copilot was to perform specific tasks that I did not know the code for and to make my coding faster when I did know the code.
