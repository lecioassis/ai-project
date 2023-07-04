# Real-Time Music Recommendation: Contextualized Algorithm for Playlist Personalization
> **_NOTE:_** This README file will be updated to its proper format further in the development of the project. For now it is a copy of the english version of the SUMMARY. 

![robot dj](readme/robot.jpg)

## Thoughts
1. The data folder is and is supposed to be empty for the fase of the project we are in. Some data is to big to be commited, others are private, therefore, must be created by the user of the application itself. 
2. The project is still in early stages, unfortunatelly and as expected the most ambitious part is to be developed after achieving a solid base. 
3. This solution is not supported by the company we request the data and is an academic and experimental project, not a commercial use application.

## Issues

1. The requests to the API are limited and there is no way to get any complete dataset;
2. Historic tracks only have Track Name and (One) Artist Name, therefore, getting the ID from non-unicode named tracks results in failure;
    - Exemplos:
      - [ÐÐ½Ð¾Ð²Ñ Ð¸ ÐÐ½Ð¾Ð²Ñ	](https://open.spotify.com/track/2i5stbgx5ZOScBITQFeS8F?si=089ecd32f8d34372)
      - [紅蓮華](https://open.spotify.com/track/23DbzwNJSLo7nkSWjODMvY?si=c474baa56dc3499f)
      - [Я не коммунист](https://open.spotify.com/track/5z7q66tSLgt23wPtCm5z3x?si=575cdb075c6449a7)
3. Image and Sound emotion analysis is a field barely developed, the most expected part of the project is postponed;
