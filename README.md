# Spotify2Youtube
The goal of the project is to provide the tools that will allows users to migrate their music playlist from Spotify to Youtube.


Pre-steps:
1. You must have an account at Spotify.
2. You must have a playlist at Spotify.
3. The web browser with DevTools is required (Chrome or Firefox).


## Part I:
Steps:
1. Login at your Spotify account in [web application](https://open.spotify.com/).
2. Go to you playlist.
<img src="https://github.com/Menober/spotify2youtube/blob/master/images/1.png">
3. Scroll whole playlist to make sure that web browser loaded all songs titles.
<img src="https://github.com/Menober/spotify2youtube/blob/master/images/2.png">
4. Open web browse DevTools (Ctrl+Shift+I for Google Chrome).
<img src="https://github.com/Menober/spotify2youtube/blob/master/images/3.png">
5. Click "Select element", then click at any song title (just like in the picture).
<img src="https://github.com/Menober/spotify2youtube/blob/master/images/4.png">
6. Scroll DevTools content up till you find `<ol class="tracklist">` element.
<img src="https://github.com/Menober/spotify2youtube/blob/master/images/5.png">
7. Click right mouse button on it, select 'Copy' and 'Copy element'.
8. Open text editor (e.g. notepad) and paste clipboard there.
<img src="https://github.com/Menober/spotify2youtube/blob/master/images/6.png">
9. Save file with name 'playlist.txt' in the same folder as other files.

