# text-to-YouTube-Playlist

Python script that uses the YouTube API to turn a list of song names into a YouTube playlist. Runs in Google Colab notebook.

After a family member lost their song library in a failed ITunes backup, I was able to recover the relevant XML file from which I extracted song titles. This was the solution.

The only downsides are that the API is rate-limited and you must submit a form to request a cap increase, and it rarely returns the top result for that query which in very few cases is not the original song.
