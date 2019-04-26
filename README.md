# www.jasonlongshore.com

This repository contains the source code to my personal website.

## Setup

You'll need the following tools

* [fsw](https://github.com/longshorej/fsw)
* [csi](https://github.com/longshorej/csi/)

To build the site each time you change a file:

```bash
fsw csi src target/dist --ext .html --ext .css
```

You can find the rendered files in `target/dist`.

To start a webserver at [http://localhost:8000](http://localhost:8000):

```bash
python -m http.server --directory target/dist --bind localhost 8000
```

## License

This repository is provided under the [MIT License](LICENSE).
