# spotipy-crawling
This is a notebook that uses `spotipy`, a python API from spotify that let's users deal with music metadata. The code is specifically designed to collect album cover image data from certain genres
## Requirements
Requirements is in `requirements.txt`
## Collect Album Cover Image Data
1. Import the required libraries
2. Set up Spotify developer's account, and retrive Client ID and Secret
3. Follow the notebook to check what genres are available
4. In the function `sp.recommendations()`, change the `seed_genres` parameter to get album covers for a certain genre of your choice
5. Follow the rest of the notebook and check the downloaded album cover images
## References
- `spotipy` documentation is used as reference ([link](https://spotipy.readthedocs.io/en/2.18.0/))
- This [medium article](https://medium.com/@maxtingle/getting-started-with-spotifys-api-spotipy-197c3dc6353b) by Max Tingle was referenced for creating Client ID and Secret
