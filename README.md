# SoundSafariSong Recommendation System

SoundSafari is a web application designed to recommend songs to users based on their preferences for various musical attributes. It offers a personalized music recommendation experience by allowing users to specify their preferences, which are then matched against a dataset of songs.

## Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/chethanarkini/Song_Recommendation_System.git
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
3. **Configure Spotify API**:
- Update getresults.py with your Spotify client_id and client_secret.   
4. Run the Application:
   ```bash
   python app.py

## Usage

- Open `http://localhost:56015` in a web browser.
- Submit song features to get recommendations.

## How It Works
- Users input their preferences on the main page.
- The backend processes these preferences and compares them against a pre-loaded dataset of songs.
- The system selects the top 10 most similar songs based on the input criteria.
- Additional details about these songs are fetched from Spotify.
- The results are displayed on a separate page with a visually appealing interface.

## Project Structure

- `app.py`: Flask application
- `getresults.py`: Functions for Spotify and recommendations
- `dataset.pickle`: Dataset file
- `requirements.txt`: Dependencies
- `template/`: HTML templates
