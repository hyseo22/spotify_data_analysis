## Project Description

The primary aim of this project was to investigate what factors affect the popularity of the song most heavily for different genres. As there were so many genres, few of them were selected: dance, pop, electronic and R&B. The factors that were examined included energy, valence, danceability and acousticness: factors that were uniquely measured by the Spotify app. 2 of these factors were chosen to be controlled as there were so many to be considerd. The control factors were decided by comparing the values of the factors with the same index and finding the 2 characteristcs that had the most similarity: valence and danceability.

The hypothesis for this project was that different genres will have similar factors that affect the popularity the most. Furthermore, it was inferred that the average of the popularity of the songs will differ for each genre; This was the reason why the project was explored for differnet genre. 

After this investigation, an extention was done to see which key was frequently used for a song and the average popularity for tracks in each key. The correlation between these two were looked at to answer the question if a key for a song was determined by considering the average popularity of a key. As a key in major is not equal to the same key in minor, two seperate calculations were made the different modes. The expectation was that no correlation would be found for either mode.  

## Data Description

The data used was extracted from the world-wide used music app Spotify and was found in the data community website 'Kaggle'. 

18 diffent information for each 232,725 tracks across 26 genres are contained in the data and the explanation for each measure can be found in this website: https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-features/

## Analysis

<img src = "img/danceMusic_energy.png" width = "400" height = "400" > <img src="img/danceMusic_acousticness.png" width = "400" height = "400">

For all of the graphs of acousticness vs. popularity and energy vs. populairty, the correlation is between -0.1 and 0.1 with one exception. Although energy vs. popularity for 0.5<valence & danceability<= 0.5 has a correlation slightly lower than -0.1, this is not sufficient evidence to say that energy affects the popularity. Therefore, it can be concluded that neither energy nor acousticness affects the popularity significantly for dance music. Furthermore, as the range of popularity is similar amongst all of the graphs, it can be deduced that valence and danceability doesn't affect the popularity of dance music too.


<img src = "img/popMusic_energy.png" width ="400" height = "400"> <img src="img/popMusic_acousticness.png" width="400" height = "400">

Similar to the graphs of the genre dance, all of the graphs for pop music also have a very weak correlation between -0.1 and 0.05. Also, the range of the popularity doesn't change significantly for each control, containing only slight anomalies. Thus, the same conclusion can be reached for the pop genre that popularity is not affected by any of the categories.

<img src = "img/rnbMusic_energy.png" width ="400" height = "400"> <img src="img/rnbMusic_acousticness.png" width="400" height = "400"> 

R&B genre continues the pattern of having very weak correlation amongst all graph. The correlations are all close to 0 suggesting close to no correlation between popularity and energy/acousticness. Moreover, the majority of the tracks seems to stay in the similar popularity range. Once more, it can be concluded that popularity for R&B genre is not affected by any factors. 
 
 <img src = "img/electronicMusic_energy.png" width ="400" height = "400"> <img src="img/electronicMusic_acousticness.png" width="400" height = "400"> 
 
Although the number of tracks differ dramatically for each control of valence and danceability, there is still a very weak correlation in the electronic genre with the strongest correlation being -0.1202 and the weakest being 0.0393. On the other hand, the range of the popularity shows slight changes for each control yet the majority still remains inside the similar range. Therefore, it can also be concluded that danceability, valence, energy and acousticness does not affect the popularity of electronic music. 
 
 ## Extension
 
  <img src = "img/major.png" width = "700"> 
