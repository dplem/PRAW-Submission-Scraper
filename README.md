# PRAW-Submission-to-CSV-and-Image-Downloader
Uses PRAW api to convert reddit submissions from a subreddit to a csv file and downloads all top images from the same subreddit.

# Reddit Submission Scraper

Reddit Submission Scraper is a program to create a csv file with data from the top posts from a subreddit. Creates a new directory with the subreddit name and downloads images of top posts.




## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install required libraries.

```bash
pip install praw
pip install wordcloud
pip install pandas-profiling
```

## Usage

Open Jupyter Notebook environment in a directory of your choice. Enter the name of the subreddit you want to analyze. Define the path to the directory which you would like the images to be downloaded. Define the path where you would like the CSV file to be stored.


```python
# Define name of subreddit
sub = 'itookapicture'
# Define the name of the directory to be created. Replace with your directory location.
path = 'Directory'+ sub
# Define the name of the directory for the CSV file to be stored. Replace with your directory location.
path_dir = 'Directory'
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
