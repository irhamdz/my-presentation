# Data Warehouse vs Data Lake 

A presentation about Data Warehouse versus Data Lake include definitions, key differents, flow and benefits of each other.

## Table of contents

- [Installation](#installation)
  - [Basic setup](#basic-setup)
  - [Full setup](#full-setup)
  - [Folder Structure](#folder-structure)

## Installation

The **basic setup** is for authoring presentations only. The **full setup** gives you access to all reveal.js features and plugins such as speaker notes as well as the development tasks needed to make changes to the source.

### Basic setup

The core of reveal.js is very easy to install. You'll simply need to download a copy of this repository and open the index.html file directly in your browser.

1. Download this root repository as ZIP
2. Unzip and Navigate to Data Warehouse vs Data Lake folder
3. replace the example contents in index.html with your own
4. Open index.html in a browser to view it

### Full setup

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/) (4.0.0 or later)

1. Clone this root repository
   ```sh
   $ git clone https://github.com/irhamdz/my-presentation.git
   ```

1. Navigate to the Data Warehouse vs Data Lake folder
   ```sh
   $ cd data-warehouse-vs-data-lake/
   ```

1. Install dependencies
   ```sh
   $ npm install
   ```

1. Serve the presentation and monitor source files for changes
   ```sh
   $ npm start
   ```

1. Open <http://localhost:8000> to view your presentation

   You can change the port by using `npm start -- --port=8001`.

### Folder Structure

- **css/** Core styles without which the project does not function
- **js/** Like above but for JavaScript
- **plugin/** Components that have been developed as extensions to reveal.js
- **lib/** All other third party assets (JavaScript, CSS, fonts, img)