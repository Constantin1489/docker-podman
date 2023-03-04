From python:3.11-alpine
RUN pip install --upgrade pip \
&& pip install yt-dlp \
&& rm -rf ~/.cache/pip \
&& chmod a+w /media
WORKDIR /media
CMD ["yt-dlp"]
