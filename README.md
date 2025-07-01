# Silero VAD Test Site

This is a simple, static HTML page for testing the Silero VAD (Voice Activity Detection) library in the browser. It uses version `0.0.22` of `@ricky0123/vad-web`.

## Launching Locally

To run this page locally, you need to serve the `index.html` file from a simple web server. This is because the page uses ES modules (`import`), which require a server environment to work correctly due to browser security policies (CORS).

One of the easiest ways to do this is with Python's built-in HTTP server.

1.  **Navigate to this directory** in your terminal:
    ```bash
    cd vad-test-site
    ```

2.  **Start the Python web server.**

    If you have Python 3:
    ```bash
    python3 -m http.server
    ```

    If you have Python 2:
    ```bash
    python -m SimpleHTTPServer
    ```

3.  **Open your browser** and go to the following URL:
    [http://localhost:8000](http://localhost:8000)

You should now see the VAD test page. You can load an audio file to test the voice activity detection.
