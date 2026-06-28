# AI Movie Trailer Generator

This is my Google Colab + Python project that creates an AI-based movie trailer.  
It uses Gemini to generate the story and trailer script, then makes a voice-over and video with MoviePy.

## How to open and run the project

1. In this GitHub repo, click on the file:
   `GGS_AI_MOVIE_TRAILER_GENERATOR.ipynb`

2. At the top, copy the notebook URL from the browser.

3. Open Google Colab in your browser.

4. In Colab, choose **File → Open notebook → GitHub tab**, and paste the URL,  
   or replace `github.com` with `colab.research.google.com/github` in the notebook link.

5. When the notebook opens in Colab, click **Runtime → Run all** to run all cells.

## How to see the trailer video

- At the end of the notebook, there are cells that use:
  `Video("final_movie_trailer.mp4", embed=True)`
  and
  `Video("cinematic_trailer.mp4", embed=True)`

- After running all cells, these cells will show and play the generated movie trailer video inside Colab.

---

Created by: **Atharv Singh Rawat**
