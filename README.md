![Olimpic Games Paris 2024](https://github.com/Lumikter/My_Spotify_Listening_Data_Analysis/blob/main/My%20Spotify%20Listening%20Data%20Analysis.png)

## Objective

This dashboard aims to provide a comprehensive and personalized overview of my Spotify listening behavior, analyzing consumption patterns, genre and artist preferences, and trends over time. Its interactive structure allows users to explore key data, such as total minutes listened, top genres, and musical trends, offering a deep understanding of how music impacts their daily life. Additionally, the filters provide flexibility to customize the analysis, tailoring it to specific interests or timeframes.

## Tools

1. SQL
   - Data Modeling.
   - Joins.
   - Views.
2. Power Bi
   - Power Query.
   - Visualization.
3. Python
   - Matplotlib.
   - Seaborn.
  
## Structure

The dashboard is structured into several key sections, each designed to highlight different aspects of my listening habits:

![Dashboard](https://github.com/Lumikter/My_Spotify_Listening_Data_Analysis/blob/main/Visualitations/MySpotifyListeningDataAnalysis-1.png)

**1. Tittle Page/General Summary**

- Project title
- Filters: Select Listening Period (Date Range), Filter by Genre, Filter by Artist, among others, allow data segmentation based on different criteria.
- Summary with key metrics: Total Minutes Listened Across All Tracks, Total Tracks Played, Total Unique Artists Played, Total Unique Genres Played and Total Unique SugGenres Played

**2. Distribution of Album vs Single Tracks**

- A pie chart showing the proportion of songs released as singles vs. albums.

**3. Distribution of Billboard vs Unrated Tracks**

- A pie chart highlighting that 79.65% of the tracks belong to Billboard, while 20.35% are unrated.

**4. Listening Time Distribution by Genre**

- A combination of bar and line charts showing total listening time by genre and cumulative percentage.

**5. Listening Time Distribution by Subgenre**

- Similar to the genre chart, but focused on subgenres.

**6. Listening Time by Hour of the Day**

- A histogram visualizing peak listening times during the 24-hour day, identifying patterns of high activity during specific hours.

**7. Tracks Listened to by Release Year**

- A scatter plot analyzing the tracks listened to by their release year.

**8. Top 100 Tracks by Total Plays and Replays**

- A scatter plot showing the most replayed songs based on total listening minutes and number of replays.

**9. Listening Time by Country**

- A bar chart that highlights the countries contributing the most to total listening time.

**10. Yearly Trends of Listening Time by Genre**

- A stacked area chart analyzing the evolution of listening time by genre over the years.

**11. Top 5 Artists by Listening Time**

- A boxplot comparing total listening time across the top five most played artists.

## Data Analysis

**1. Cover Page/General Summary**

- Project title
  
![Tittle](https://github.com/Lumikter/My_Spotify_Listening_Data_Analysis/blob/main/Visualitations/tittle.png)

- Filters

![Filters](https://github.com/Lumikter/My_Spotify_Listening_Data_Analysis/blob/main/Visualitations/filters.png)

- Summary with key metrics
  
![KPI](https://github.com/Lumikter/My_Spotify_Listening_Data_Analysis/blob/main/Visualitations/KPI.png)

**2. Distribution of Album vs Single Tracks**

Proportion of listening time dedicated to albums versus singles. The data indicates that 85.68% of the total listening time is spent on albums, while 14.32% is dedicated to singles. This suggests a preference for longer and more cohesive musical experiences over individual tracks. Also, this reflects a structured, analytical mindset that seeks to understand the bigger picture before making decisions or taking action.

![AlbvSing](https://github.com/Lumikter/My_Spotify_Listening_Data_Analysis/blob/main/Visualitations/AlbumsvsSingles.png)

**3. Distribution of Billboard vs Unrated Tracks**

This chart compares the distribution of songs that are part of Billboard-listed tracks versus unrated songs. A significant majority, 79.65%, corresponds to unrated songs, while 20.35% are Billboard hits. This finding highlights the inclination towards exploring lesser-known or independent music outside mainstream trends.

Favoring music outside mainstream charts demonstrates curiosity and the ability to explore alternatives beyond popular trends. This highlights adaptability and creativity in finding innovative solutions. This skill aligns well with roles that demand innovative thinking, such as process improvement or the adoption of emerging tools and methods.

![BilvUnr](https://github.com/Lumikter/My_Spotify_Listening_Data_Analysis/blob/main/Visualitations/BillboardvsUnrated.png)

**4. Listening Time Distribution by Genre**

Rock dominates with over 200k minutes listened, representing 53% of the total time. This highlights a strong personal affinity toward this genre. Electronic music ranks second, contributing to 76% of cumulative listening time. Other genres like pop, funk, and Latin music make up the remaining 24%. Over 85% of listening time is focused on just two genres (Rock and Electronic). This indicates a highly specialized taste in music.

While the primary genre is predominant, certain secondary genres account for a substantial amount of listening time, indicating a moderate diversity in musical tastes.

![Genre](https://github.com/Lumikter/My_Spotify_Listening_Data_Analysis/blob/main/Visualitations/AcumulatedGenres.png)

**5. Listening Time Distribution by Subgenre**

Pop Rock is the most listened-to subgenre, with 80k minutes (22%), followed by Alternative Rock at 34%. This reflects a preference for more modern and varied styles within Rock. Subgenres like Progressive House, Disco, and Nu Metal are represented, showing some diversity but with a predominant focus on Rock and Electronic. Less-represented subgenres (Synth Pop, J Rock, etc.) could be explored further to diversify the musical experience.

Pop Rock and Alternative Rock subgenres dominate the accumulated listening time, accounting for nearly a quarter of all minutes. This indicates a strong preference within these primary genres. Compared to the overall genre distribution, there is a more even spread among subgenres. This suggests listeners are delving deeper into their favorite styles. Although subgenres like Synth Pop and Progressive House have lower listening times, their presence hints at a curiosity to explore less mainstream genres, reflecting an openness to new musical experiences.

This analysis points towards a balanced personality: a desire for familiar styles combined with a willingness to discover new music. It could also suggest an analytical mindset that can identify trends and explore alternative options with a strategic curiosity.

![Subgenre](https://github.com/Lumikter/My_Spotify_Listening_Data_Analysis/blob/main/Visualitations/AcumulatedSubGenres.png)

**6. Listening Time by Hour of the Day**

Distribution of listening time across different hours of the day. The highest listening activity occurs around 8 AM, with over 74,157 minutes dedicated to music at this time. Other notable peaks occur around 6 PM and 8 PM, suggesting that listening habits align closely with evening leisure periods. Lower activity is observed in the early morning and late-night hours. The concentrated listening times in the morning suggest that music is a primary activity for relaxation or focus before and after work hours.

High listening activity during morning hours suggests optimal performance in quieter, distraction-free moments. This reflects an ability to focus deeply on complex tasks or adapt to flexible working hours when necessary. This tendency is beneficial for roles involving data analysis or problem-solving, especially when handling high-priority projects requiring extended concentration.

![HpurDay](https://github.com/Lumikter/My_Spotify_Listening_Data_Analysis/blob/main/Visualitations/HourListened.png)

**7. Tracks Listened to by Release Year**

Looking at the scatter plot showing the total accumulated minutes by decade, it is clear that the playlist reflects a strong preference for more recent decades, with a marked inclination towards music from the 2000s and 2010s.

2000s and 2010s: These two decades show the highest accumulated minutes, with 107,002 minutes in the 2000s and 107,686 minutes in the 2010s. This highlights a significant preference for contemporary music, suggesting a resonance and connection with modern sounds. These decades also correspond with the rise of genres like modern rock, electronic, and pop, which aligns with the tendency to listen to both classic and more current genres, as seen in the top 100 tracks.

1990s: With 89,530 minutes, the 90s still hold relevance for you, showing a strong presence of rock and electronic music, with a focus on the rise of bands and international artists that defined the generation, such as grunge and alternative rock groups.

1980s: Despite being a crucial decade in the evolution of genres like rock and electronic, this decade shows only 71,506 minutes. This may reflect a lesser personal affinity for the musical styles that dominated that era, although it still plays a significant role in the formation of your musical repertoire.

Earlier Decades (1960s and 1970s): Music from the 1960s and 1970s shows much less presence in terms of accumulated minutes, with 1,291 minutes in the 60s and 9,323 minutes in the 70s. While some genres and artists from these eras may have influenced the musical taste, it seems a prefer more recent and current sounds, with the music from these earlier decades not forming a significant part of the repertoire.

The plot highlights a clear preference for music from the last two decades, especially the 2000s and 2010s, indicating that I have adapted to musical changes and connect with more modern sounds. At the same time, there is a slight connection to earlier decades, but in a much more limited way.

![RelYear](https://github.com/Lumikter/My_Spotify_Listening_Data_Analysis/blob/main/Visualitations/TracksbyDecade.png)

**8. Top 100 Tracks by Total Plays and Replays**

The analysis reveals unique patterns that reflect your musical tastes and the type of emotional connection you have with music. Rock is the predominant genre, with songs like "You Get What You Give" by New Radicals and "Bizarre Love Triangle" by New Order leading the list. These tracks, with their high play counts, suggest that this genre holds significant nostalgic and emotional value, likely forming the foundation of many of musical experiences. Electronic music also plays a crucial role, highlighted by tracks like "Boundary Layer - Original Mix" and "Heartbeat - Nicky Romero Edit". This suggests that, in addition to enjoying the classics, a strong inclination towards genres that offer a more immersive, modern experience, possibly seeking the energy and dynamism of electronic music. The repetition of these songs emphasizes how electronic music has greater fidelity and consistency in listening habits. Genres like funk and pop complement the musical repertoire, though with less weight compared to Rock and Electronic. This could reflect an appreciation for sonic diversity and a desire to explore different moods through music. Latin genres also show a growing presence, with songs like "Huellas - Live From Santiago Chile/1999", which may reflect the cultural roots or a preference for sounds that bring warmth and emotion.

![TopTracks](https://github.com/Lumikter/My_Spotify_Listening_Data_Analysis/blob/main/Visualitations/Top100Tracks.png)

**9. Listening Time by Country**

The United States and the United Kingdom dominate the chart, indicating a preference for artists or musical styles from these regions. Argentina and Mexico are well-represented, likely due to a cultural connection with genres like Latin Rock.  While there’s a mix of countries, listening is concentrated in a few regions. This could be an opportunity to explore music from other cultures.

The inclusion of countries like Germany and Japan indicates an interest in music from less mainstream cultures. This might reflect the influence of global genres such as K-Pop or European electronic music. While Anglo-Saxon artists dominate total listening time, Latin artists have a notable presence, particularly within subgenres. The data shows that despite a focus on certain genres and regions, there's a clear appetite for exploring new sounds and cultures.

![TopCoun](https://github.com/Lumikter/My_Spotify_Listening_Data_Analysis/blob/main/Visualitations/countrieslistentracks.png)

**10. Yearly Trends of Listening Time by Genre**

![Trends](https://github.com/Lumikter/My_Spotify_Listening_Data_Analysis/blob/main/Visualitations/TrendsListenGenres.png)

**11. Top 5 Artists by Listening Time**

The Minutes by Artist chart displays the distribution of accumulated listening minutes for your top five most-played artists: Alejandro Sanz, Coldplay, New Radicals, Purple Disco Machine, and Red Hot Chili Peppers. By analyzing the boxplot, we can uncover intriguing patterns.

The main box represents the interquartile range (Q1 to Q3) and provides insight into the variability of listening minutes for each artist. A wider box may indicate greater dispersion in the time spent listening to that artist, while a narrower one suggests more consistent listening habits. The whiskers display non-outlier values beyond this range, and the outliers highlight uncommon listening sessions, potentially driven by repeated plays of specific tracks or entire albums.

Looking at individual artists, Alejandro Sanz, known for romantic ballads, may reflect listening sessions during calmer or introspective moments. Coldplay, blending pop and alternative rock, appears suitable for both relaxation and tasks requiring energy. New Radicals, with their iconic single album, likely show less variability in accumulated minutes, though outliers may represent repeated plays of their hit song You Get What You Give. Purple Disco Machine, with its electronic and dance music, is likely preferred for active moments or longer listening sessions. Meanwhile, Red Hot Chili Peppers, with their mix of funk and rock, may correspond to more energetic or high-activity moments.

![TopArtist](https://github.com/Lumikter/My_Spotify_Listening_Data_Analysis/blob/main/Visualitations/MinutesbyArtist.png)

## Conclusion

The analysis highlights a profound connection to music as an essential part of my life, reflected in over 401 thousand minutes of listening and a remarkable diversity of genres, artists, and subgenres played. Rock emerges as the leading genre, alongside a strong preference for singles and Billboard hits. Listening habits reveal a consistent pattern, with peak activity during the day and a notable inclination toward artists from the United States, the UK, and Latin America. Over time, the trends show a growing interest in alternative and electronic genres, demonstrating an openness to exploring new musical landscapes. This analysis not only celebrates the user’s emotional connection to music but also provides valuable insights to enhance future listening experiences.
