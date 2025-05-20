### Rabo do Peixe flashcards

  * Portuguese to English flashcards for the unique words in each episode.


## How it was created

  * Get the subtitles
    * Play an episode on Netflix.
    * Pause and open developer tools (right click on the page and select `Inspect`)
    * Click on the network tab.
    * Add the filter `/?o=`
    * Refresh the page. A result should appear, if it doesn't choose a subtitle from the Netflix UI.
    * Click on the response tab.
    * Copy paste the output to a .ttml file.
  * Get the unique words.
    * Get copilot to write a script that extracts the unique words from the file.
  * Upload the file to Gemini and ask it to create a single html file that shows each word and its translation as flashcards.
  * Fine tune the look and behaviour.
  