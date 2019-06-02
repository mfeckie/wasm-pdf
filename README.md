# PACK-PDF
## Generate PDF files on the browser with JavaScript and WASM (WebAssembly).

Idea here is to push all the work involved in creating a PDF to the browser side, instead of using precious server resources.

**This library is working, but is also Work In Progress, so I don't recommend using it in anything serious yet.**

## Demo

Example that generated a sample PDF document

**[View Demo](https://jussiniinikoski.github.io/pack-pdf-demo/)**

## How to generate an example PDF

* First install [the Rust compiler](https://www.rust-lang.org)
* Clone this repo:```git clone https://github.com/jussiniinikoski/pack-pdf.git```
* Change to directory: ```cd pack-pdf```
* Install JavaScript libraries: ```npm install```
* Launch the local development server: ```npm run serve```
* Open your browser and visit the url provided by the server, usually ```http://localhost:8080```

## License

This project is licensed under either of

 * Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or
   http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license ([LICENSE-MIT](LICENSE-MIT) or
   http://opensource.org/licenses/MIT)
