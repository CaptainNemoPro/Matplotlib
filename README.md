# Matplotlib

# Intoduction

![alt text](https://th.bing.com/th/id/OIP.emp_VGrhbsTCL6OXk8bbKQHaCD?pid=ImgDet&w=720&h=200&rs=1)

Are you a music enthusiast who loves to keep track of latest music and albums. This project will help you know which artist is trending and which type of music has been trending on Spotify and Youtube. With the being said, lets take a cursory look at the variables given in this dataset.

# About the dataset

Dataset of songs of various artist in the world and for each song is present:

1. Several statistics of the music version on spotify, including the number of streams;
2. Number of views of the official music video of the song on youtube.

It includes 26 variables for each of the songs collected from spotify. These variables are briefly described next:


1. Track: name of the song, as visible on the Spotify platform.
2. Artist: name of the artist.
3. Url_spotify: the Url of the artist.
4. Album: the album in wich the song is contained on Spotify.
5. Album_type: indicates if the song is relesead on Spotify as a single or contained in an album.
6. Uri: a spotify link used to find the song through the API.
7. Danceability: describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable.
8. Energy: is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy. For example, death metal has high energy, while a Bach prelude scores low on the scale. Perceptual features contributing to this attribute include dynamic range, perceived loudness, timbre, onset rate, and general entropy.
9. Key: the key the track is in. Integers map to pitches using standard Pitch Class notation. E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on. If no key was detected, the value is -1.
10. Loudness: the overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks. Loudness is the quality of a sound that is the primary psychological correlate of physical strength (amplitude). Values typically range between -60 and 0 db.
11. Speechiness: detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks.
12. Acousticness: a confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic.
13. Instrumentalness: predicts whether a track contains no vocals. "Ooh" and "aah" sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly "vocal". The closer the instrumentalness value is to 1.0, the greater likelihood the track contains no vocal content. Values above 0.5 are intended to represent instrumental tracks, but confidence is higher as the value approaches 1.0.
14. Liveness: detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live.
15. Valence: a measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry).
16. Tempo: the overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration.
17. Duration_ms: the duration of the track in milliseconds.
18. Stream: number of streams of the song on Spotify.
19. Url_youtube: url of the video linked to the song on Youtube, if it have any.
20. Title: title of the videoclip on youtube.
21. Channel: name of the channel that have published the video.
22. Views: number of views.
23. Likes: number of likes.
24. Comments: number of comments.
25. Description: description of the video on Youtube.
26. Licensed: Indicates whether the video represents licensed content, which means that the content was uploaded to a channel linked to a YouTube content partner and then claimed by that partner.
27. official_video: boolean value that indicates if the video found is the official video of the song.

# Insights

Based on the two horizontal bar charts, we can observe that the top 10 artists by views and streams are quite different.
In terms of views, the chart shows that Ed Sheeran is the most viewed artist, followed by Justin Bieber and Shakira. This suggests that these artists have a broad and engaged audience, and their music is popular across different demographics.
On the other hand, the chart for streams indicates that Drake is the most streamed artist, followed by Post Malone and J Balvin. This suggests that these artists have a strong presence on streaming platforms and their music is particularly popular among younger audiences who prefer to listen to music online.
Interestingly, while some artists appear in both charts, their rankings can be quite different. For example, Ariana Grande is ranked fourth by views but doesn't appear in the top 10 by streams. This could suggest that her music is more likely to be watched on video platforms rather than streamed on audio platforms.
Overall, these charts provide insights into the popularity of different artists and their presence across different platforms. It can be useful for music industry professionals and researchers to understand these trends and use them to inform their strategies and decisions.