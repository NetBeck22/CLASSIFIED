# CLASSIFIED

**An immersive data-awareness experience about what it feels like to be reduced to a profile.**

CLASSIFIED is a small, vibecoded art installation built around a simple idea: some things are easier to understand when you experience them, not just read about them. Immersive art can make an abstract system feel personal. This piece invites you to step inside the uneasy logic of algorithmic profiling and notice how quickly a handful of details can become a story about a whole person.

## The experience

In this 6–8 minute, single-person experience, you enter a few details and watch a fictional system turn them into a confident-looking personal dossier. A cinematic journey through data points, ambient sound, animation, and on-screen conclusions leads to a reveal: the system does not know you. It knows patterns, guesses, and people you might resemble.

The experience ends by connecting that feeling to real-world decisions shaped by data, such as insurance, credit, and recommendation feeds. Its aim is to prompt reflection, not to assess or classify the participant.

## Try it

No build step or dependencies are required. Open [`classified.html`](classified.html) in a modern desktop or mobile browser, then choose **BETREED DE INSTALLATIE** to begin. For a local web server instead:

```bash
python3 -m http.server 8000
```

Open [http://localhost:8000/classified.html](http://localhost:8000/classified.html). The experience is in Dutch. Sound starts after you enter the installation; adjust or mute it with your device's volume controls.

## Privacy and fiction

- The profile and conclusions are fictional, generated in the browser from simple rules and random values. They are not a real prediction, score, or evaluation of the participant.
- The page does not store or transmit the details you enter. An optional photo is read locally in your browser and is not uploaded.
- The page requests fonts from Google Fonts. As with other externally hosted resources, loading those fonts may connect your browser to Google. The experience itself has no analytics or backend service.
- Consider using made-up details if you would rather not enter personal information.

## Built with

One self-contained HTML file using HTML, CSS, vanilla JavaScript, Canvas, and the Web Audio API. Google Fonts provide the typography; no package installation is needed.