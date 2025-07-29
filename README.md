# navidrome-now-playing
A small custom css file that removes most of the navidrome page, leaving just the rotating album art, song title, and artist name.

I made this because I have a navidrome media server, and I wanted a way to show my currently playing song in OBS, for streaming.

## Usage

1. Create a browser source in OBS with the navidrome url of an album or playlist that you want to play on stream/recording.
2. Log into your navidrome instance in the browser source (right click -> interact)
3. Start playing the album/playlist to ensure that the browser source has that specific album/playlist selected. (im not 100% sure if this is necessary)
4. Copy the contents of ``custom.css`` into the Custom CSS section in the browser source's properties.
5. Enjoy! (You can crop-resize the browser source in the OBS preview by holding ALT while resizing it.)

Hint: You can use the arrow keys to skip or go back in the song list and the spacebar to play/pause when the interact window is focused.


## Screenshots
(as you can see, the now-playing indicator is in the top-left of the recording) 
<img width="1593" height="894" alt="image" src="https://github.com/user-attachments/assets/3125ebc3-7584-425e-9f2f-805914462a6e" />
