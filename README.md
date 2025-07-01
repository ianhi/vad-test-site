# Silero VAD Test Site

This is a simple, static HTML page for testing the Silero VAD (Voice Activity Detection) library in the browser. It uses version `0.0.22` of `@ricky0123/vad-web`.

For more information on the VAD library, please refer to the official documentation: [https://docs.vad.ricky0123.com/](https://docs.vad.ricky0123.com/)

## Launching Locally

To run this page locally, you need to serve the `index.html` file from a simple web server. This is because the page uses ES modules (`import`), which require a server environment to work correctly due to browser security policies (CORS).

One of the easiest ways to do this is using `npx serve`, which provides a simple static server with hot-reloading capabilities.

1. **Navigate to this directory** in your terminal:

    ```bash
    cd vad-test-site
    ```

2. **Start the web server using `npx serve`.** If you don't have `serve` installed globally, `npx` will temporarily install it for you.

    ```bash
    npx serve .
    ```

3. **Open your browser** and go to the URL provided by `serve` (usually [http://localhost:5000](http://localhost:5000)).

You should now see the VAD test page. You can load an audio file to test the voice activity detection.

You should now see the VAD test page. You can load an audio file to test the voice activity detection.
