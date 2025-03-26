# WebGL Earth Offline Demo

This repository demonstrates the WebGL Earth API using custom map tiles derived from Natural Earth data.

The tiles are rendered using [MapTiler](http://www.maptiler.com/). For guidance on creating custom map tiles, refer to this [step-by-step tutorial](http://www.maptiler.com/how-to/3d-online-globe/).

## Getting Started

1. Download and extract this repository, or clone it using Git:
    ```
    git clone https://github.com/liamsmith413/webgl-earth-offline
    ```
2. Note that this example runs offline but requires serving the files over the HTTP protocol. Directly opening the HTML file in a browser will not work due to security restrictions on loading WebGL textures.

3. To view the globe, host the files on a web server. Once hosted, the application will function as expected.

## Local Development

To develop locally, ensure you are running an HTTP server. For example, you can use Python's built-in HTTP server:

```bash
python -m http.server
```

## Live Demo

A live demo is available at: [https://webgl-earth-offline.vercel.app/](https://webgl-earth-offline.vercel.app/)

## Demo Video

Watch the demo video: [demo/demo.mp4](demo/demo.mp4)