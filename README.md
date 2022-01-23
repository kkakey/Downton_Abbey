# Downton Abbey Transcripts

<img src="https://www.hellomagazine.com/imagenes/film/20210826120441/downton-abbey-release-title-film-sequel-a-new-era/0-581-980/downton-abbey-cast-t.webp?filter=high" alt="image of the cast of Dowton Abbey, a historical British drama television series" width="300" >

Data in this repository comes from [Forever Dreaming](https://transcripts.foreverdreaming.org/).

## The Dataset

- `seasons_1-3.4_scripts` - line-by-line transcripts of Downton Abbey from Season 1 episode 1 to Season 3 episode 4. Includes the name of the character speaking, the line they spoke, as well as the scene, line and episode number.

## Data Dictionary

### `DowntonAbbey-seasons_1-3.4_scripts.csv`

|variable        |class     |description |
|:---------------|:---------|:-----------|
|Speaker    |character | Name of the character speaking |
|Text            |character | Line the character spoke |
|Scene            |integer | Scene number in the episode |
|Episode            |character    | Season and episode number
|line_order_in_episode            |integer    | Line number in the episode

********************************************************

Script to retrieve the data: 
- [webscraping_script.Rmd](https://github.com/kkakey/Downton_Abbey/blob/main/webscraping_script.Rmd)

********************************************************

Note: Unfortunatly transcripts from additional episodes and seasons could not be retrieved in this same format due to less information being provided for these later epsidoes.
