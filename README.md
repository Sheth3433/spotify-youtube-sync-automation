# Spotify to YouTube Playlist Automation

This project is an automation workflow built using **n8n** that syncs Spotify liked songs to a YouTube playlist.

## How It Works

1. Fetches liked songs from Spotify
2. Extracts track name and artist
3. Searches the song on YouTube
4. Finds the best matching video
5. Adds it automatically to a YouTube playlist

The workflow runs automatically every few hours using a scheduled trigger.

## Tech Stack

- n8n
- Spotify API
- YouTube Data API
- OAuth2 Authentication
- HTTP Requests

## Workflow Overview

Spotify Liked Songs  
↓  
Search YouTube  
↓  
Check Video Exists  
↓  
Add to Playlist

## Setup

1. Import `workflow.json` into n8n
2. Add your Spotify credentials
3. Add your YouTube API key
4. Set your YouTube playlist ID

## Screenshots

See the `screenshots` folder.

## Future Improvements

- Better video matching
- Duplicate filtering
- Playlist management
