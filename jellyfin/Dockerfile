FROM jellyfin/jellyfin
RUN apt-get update && apt-get install -y \
    yt-dlp \
    python3-pip \
    nano
RUN python3 -m pip install -U yt-dlp
