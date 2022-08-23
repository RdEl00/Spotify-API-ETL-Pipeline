# Spotify ETL Project

This is a simple data pipeline to extract **my tracks record** using the **spotify api** and save the songs listened to everyday into a local **sqlite db**.

I achieved this project by following Karolina's [data engineering for beginners' course.](https://github.com/karolina-sowinska/free-data-engineering-course-for-beginners) I highly recommend checking her [Youtube channel.](https://www.youtube.com/channel/UCAxnMry1lETl47xQWABvH7g)


## Motivation

I wanted to create a simple ETL which would help develop my Data engineering skills. Spotify API was a good place to explore this.

## Architecture
 <br>
<img src="images/spotify flowchartt.png">

-  Extract data using [Spotify API](https://developer.spotify.com/documentation/)
-  Load data into [Sqlite](https://www.sqlite.org/index.html)

## Setting up the Project

- Clone the repository using

```bash
git clone https://github.com/RdEl00Spotify-API-ETL-Pipeline.git
```

- Open the terminal/cmd and navigate to the project folder.

```bash
cd Spotify-API-ETL-Pipeline
```

- Install the requirments.txt using

```bash
pip install -r requirments.txt
```
- Open the script.py file, add your spotify username & the token.

```bash
USER_ID = ""
TOKEN = ""
```
## Usage

- Now run the `script.py` using

```bash
python script.py
```

Congrats! your 24h tracks dataset should now be created :)