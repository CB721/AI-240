# Final Machine Learning Project

## Student - Clinton Brodar
## Instructor - Dr. Uma Gajendragadkar

### Problem - Develop a ML model to predict the effect of music on mental health

### Dataset source - https://www.kaggle.com/datasets/catherinerasgaitis/mxmh-survey-results

This dataset consists of 736 observations & 33 numerical independent variables.
Dependent and target variable is `Music effects`.

#### Music effects
`Improve      542`
`No effect    169`
`Worsen        17`

Because there are so few rows with Worsen, these will be merged with No effect and that new value will become No Improve.

#### Column Descriptions

Timestamp - Date and time when form was submitted

Age - Respondent's age

Primary streaming service - Respondent's primary streaming service

Hours per day - Number of hours the respondent listens to music per day

While working - Does the respondent listen to music while studying/working?

Instrumentalist - Does the respondent play an instrument regularly?

Composer - Does the respondent compose music?

Fav genre - Respondent's favorite or top genre

Exploratory - Does the respondent actively explore new artists/genres?

Foreign languages - Does the respondent regularly listen to music with lyrics in a language they are not fluent in?

BPM - Typical speed of music the listener listens to

Anxiety - Scale of listener anxiety level (0 - 9)

Depression - Scale of listener depression level (0 - 9)

Insomnia - Scale of listener insomnia level (0 - 9)

OCD - Scale of listener OCD level (0 - 9)

Music effects - Class variable