# SplitScreenChatStats

A mobile-friendly GitHub Pages dashboard for the quota-efficient hybrid workflow:

- **Top panel:** Aaron Parecki's live chat overlay URL.
- **Bottom panel:** a live viewer or statistics page.
- **Chat helper:** opens a YouTube live-chat pop-out from a video ID.
- **Resizable layout:** drag the blue divider, or change the saved layout by dragging.

## How to use

1. Sign in to YouTube in the browser where Aaron Parecki's extension is installed.
2. Open the YouTube live-chat pop-out using the video ID field.
3. Use Aaron's extension to create/get the overlay URL, including its unique session ID.
4. Paste that full overlay URL into **Aaron overlay URL** and press **Go**.
5. Paste your live viewer/statistics URL into the bottom field and press **Go**.
6. Copy the same Aaron overlay URL into the YoloBox Ultra browser source.

The dashboard does **not** request, store, or transmit your YouTube password. It does not use the YouTube Data API and therefore does not consume YouTube API quota. The YouTube login remains in the browser that opens the chat pop-out.

## Important limitation

GitHub Pages cannot inspect YouTube chat inside an iframe because of browser same-origin security. The Aaron extension must run on the YouTube chat page and provide the overlay session URL. This project is the dashboard/display side of that workflow; it does not replace the extension.

The live page is available after enabling GitHub Pages for the `main` branch and root folder:

`https://skysquadtv.github.io/SplitScreenChatStats/`
