# The Geography of Chekhov's Plays 
This repository contains dataset of the places, real and fictional, and their attributes mentioned in Anton Chekhov's four major plays. The file is available for download in CSV form. 

## Data Structure 
For each of the plays, data was collected on all places mentioned - both real and fictional. Places mentioned more than once in a given act were recorded once, with new plot, character, and quote information added to the existing entry. For places mentioned in multiple acts, an entry for each act was made. For example, in the data for Three Sisters, there are four entries for "Moscow" (one for each of the four acts), and all 18 mentions of "Moscow" in Act I are recorded in a single entry.

## Variables
* obj_name - the name of the place, usually as it is referred to in the story
* type - the type of place, a categorical variable with a range of choices, such as "estate", "educational institution", "forest", "factory", "garden", "river", "restaurant" and so on.
* status - a categorical variable, either "real" or "fictional"
* role_in_play - a categorical variable, either "setting" or "mentioned"
* modern_location_eng - the location of the place as it is currently known in English; N/A for fictional places
* modern_location_rus - the location of the place as it is currently known in Russian; N/A for fictional places
* historic_location_eng - the location of the place as it was known during the period of the play in English; N/A for fictional places
* historic_location_rus - the location of the place as it was known during the period of the play in Russian; N/A for fictional places
* relative_location - the location of the place with respect to the play's central estate; can be used to construct a relative geography of fictional and real places
* location_exists_today - a categorical variable, either "yes" or "no"
* play - a categorical variable detonating the play to which the entry corresponds
* act - a categorical variable detonating the act to which the entry corresponds
* page_num - the page number corresponding to the place mention in the Norton Critical Edition of Anton Chekhov’s Selected Plays (translated and edited by Laurence Senelic)
* quote_eng  - the quote, in translation, mentioning the place; all English excerpts are from the Norton Critical Edition
* quote_rus - the quote, in the original Russian, mentioning the place; all Russian excerpts are from the Fundamental Digital Library of Russian Literature and Folklore 
* plot_notes - a brief note about the plot at the moment of the mention 
* hist_notes - a brief note on the history of the place (optional)
* geo_notes - a brief note on the geography of the place, including changing toponyms or jurisdictions (optional)
* lat - the place's approximate latitude in decimal degrees 
* lng - the place's approximate longitude in decimal degrees 
* characters - characters onstage during the mention
* time - the time of day or year when the mention occurs (optional)
* sources - a number corresponding to an entry in a source table that lists the source of geographic or historical notes (optional)

## License 
Creative Commons Attribution-Noncommerical 
https://creativecommons.org/licenses/by-nc/3.0/legalcode 
