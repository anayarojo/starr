# starr
Starr Apps to build your home server

- Transmission (torrents)
- Plex (library management)
- Overseerr (media discovery and request management)
- Prowlarr (indexers)
- Radarr (movies)
- Sonarr (tv shows)

Also, you can add import lists from (IMDB, Letterboxd, and many other options)

Start by creating the following volumes to mount:

- **Apps** is where your app config will live
- **Downloads** is where your torrent downloads will exist for a short period of time
- **Media** is where your content will live
- **Torrents** is where you can add manual torrents to watch (and start downloads from there, not very common, but required by Transmission)

<img width="241" height="385" alt="image" src="https://github.com/user-attachments/assets/4966bdee-4b56-4e79-b0cf-d09a8b86f16d" />

Rename `.env.example` file to `.env` and enter the following variables:

- `CONTAINER_NAME_PREFIX=starr_`
- `HOME_DIR=/Users/joseestrada/home` (you can add a different unit, or directory under your main disk)
- `TIME_ZONE=America/Hermosillo` (recommended to match hours between your apps) 😉
