# Music Recommender System

This project involves building a music recommender system using Python and various libraries such as Streamlit and Spotipy. The system provides music recommendations based on a selected song and displays album covers of the recommended songs.

## Project Overview
The main goal of this project is to recommend similar songs to a user-selected song, enhancing the music discovery experience. By analyzing song features and utilizing the Spotify API, the system identifies and recommends tracks that match the user's musical preferences.

## Dataset
The dataset used in this project is too large to be uploaded to GitHub directly. You can download the dataset file from [Here](https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset).

## Requirements
To run the code in the Streamlit application, you will need the following Python libraries installed:
- pandas
- spotipy
- streamlit
- scikit-learn

## Setup Instructions
1. **Clone the repository**:
    ```shell
    git clone https://github.com/yourusername/music-recommender-system.git
    ```
2. **Navigate to the repository directory**:
    ```shell
    cd music-recommender-system
    ```
3. **Create a virtual environment (optional but recommended)**:
    ```shell
    python -m venv venv
    ```
4. **Activate the virtual environment**:
    - On Windows:
        ```shell
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```shell
        source venv/bin/activate
        ```
5. **Install the required packages**:
    ```shell
    pip install -r requirements.txt
    ```
6. **Set up your Spotify API credentials**:
    - Create a `credentials.txt` file in the project root directory.
    - Add your Spotify client ID and secret key to the file, each on a new line:
        ```plaintext
        client_id
        client_secret
        ```
7. **Start the application**:
    ```shell
    streamlit run app.py
    ```

## How to Use
1. Run the application using `streamlit run app.py`.
2. In the application, select a song from the dropdown menu or type the name of a song.
3. Click the 'Show Recommendation' button to view recommended songs and their album covers.

## Contributing
Contributions to this project are welcome! If you find any issues or would like to add new features, please feel free to submit a pull request.

## Acknowledgments
- [Streamlit](https://streamlit.io/) for providing the interactive web interface.
- [Spotipy](https://spotipy.readthedocs.io/) for integrating with the Spotify API.
- [Spotify API](https://developer.spotify.com/) for providing music data and album covers.
