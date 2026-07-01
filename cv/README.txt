Put your CV file in this folder, for example: My-CV.pdf

Then open index.html, find this line (search for "downloadCvBtn"):

  <a id="downloadCvBtn" class="btn-home2" href="cv/My-CV.pdf" download="Amine-CV.pdf">

...and change:
  - href="cv/My-CV.pdf"   -> the exact filename you put in this folder
  - download="Amine-CV.pdf" -> the filename you want people to see when they download it

That's it — the button will now download your real CV.
