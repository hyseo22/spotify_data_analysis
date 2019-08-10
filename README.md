## Project Description

The primary aim of this project was to investigate what factors affect the popularity of the song most heavily for different genres. As there were so many genres, few of them were selected: dance, pop, electronic and R&B. The factors that were examined included energy, valence, danceability and acousticness: factors that were uniquely measured by the Spotify app. 2 of these factors were chosen to be controlled as there were so many to be considerd. The control factors were decided by comparing the values of the factors with the same index and finding the 2 characteristcs that had the most similarity: valence and danceability.

The hypothesis for this project was that different genres will have similar factors that affect the popularity the most. Furthermore, it was inferred that the average of the popularity of the songs will differ for each genre; This was the reason why the project was explored for differnet genre. 

After this investigation, an extention was done to see which key was frequently used for a song and the average popularity for tracks in each key. The correlation between these two were looked at to answer the question if a key for a song was determined by considering the average popularity of a key. The expectation was that no correlation would be found.  

## Data Description

The data used was extracted from the world-wide used music app Spotify and was found in the data community website 'Kaggle'. 

18 diffent information for each 232,725 tracks across 26 genres are contained in the data and the explanation for each measure can be found in this website: https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-features/

## Analysis

<img src = "img/danceMusic_energy.png" width ="600" height = "600"> <img src="img/danceMusic_acousticness.png" width="600" height = "600">
For all of the graphs of acousticness vs. popularity and energy vs. populairty, the correlation is between -0.1 and 0.1 with one exception. Although energy vs. popularity for 0.5<valence & danceability<= 0.5 has a correlation slightly lower than -0.1, this is not sufficient evidence to say that energy affects the popularity. Therefore, it can be concluded that neither energy nor acousticness affects the popularity significantly for dance music. Furthermore, as the range of popularity is similar amongst all of the graphs, it can be deduced that valence and danceability doesn't affect the popularity of dance music too.

<img src = "img/popMusic_energy.png" width ="600" height = "600"> <img src="img/popMusic_acousticness.png" width="600" height = "600">
Similar to the graphs of the genre dance, 
