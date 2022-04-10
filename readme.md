# Statistical Data Viewer
## _A simple chrome extension for users to visualize the data stored on their local IPFS node_

[![made-with-javascript](https://img.shields.io/badge/Made%20with-JavaScript-1f425f.svg)](https://www.javascript.com)

IPFS Statistical Data Viewer is a Chrome Extension that visualizes your IPFS Node with D3.js using the file_type and file_size as the sources of data

- Stats(filename, filesize) are requested from users IPFS node via http api request
- D3.js uses http request to build Treemap that looks like this
![Screen Shot 2022-04-07 at 6 00 34 PM](https://user-images.githubusercontent.com/30084404/162333144-4d65b53f-0df5-49ec-bc11-40ea0bf78bc8.png)



## Features
- Static data visualization command to generate a graphic that is displayed to user
- FUTURE: Zoomable animations using D#
- FUTURE: Canvas visualizations instead of SVG

## Tech


We are building a web-app to save and monitor your data via IPFS. Our program scans your IPFS cache folder to show a detailed summary of what is stored on your IPFS node. The data will be visualized using organized colorful graphics similar to apps like Windirstat, Spacesniffer, or Disk Recon. Each file type (MP3, ZIP, EXE, JPEG, etc.) is assigned a color in a collage of rectangles that are sized depending on how much space that file type is using. 

- [IPFS] - Peer-to-peer hypermedia protocol
- [D3] - A Javascript library for visualizing data using web standards-
- [markdown-it] - Markdown parser done right. Fast and easy to extend.
- [node.js] - evented I/O for the backend
- [Express] - fast node.js network app framework [@tjholowaychuk]


## Installation

Install the dependencies and devDependencies and start the server.

```sh
npm install
```

For production environments...

```sh
Coming soon
```


## License

MIT


[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [ipfs]: <https://github.com/ipfs>
   [d3]: <https://github.com/d3/d3>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [node.js]: <http://nodejs.org>
   [jQuery]: <http://jquery.com>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>







