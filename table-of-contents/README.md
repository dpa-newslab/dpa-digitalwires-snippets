# dpa-digitalwires: Creation of a table of contents

`table_of_contents.js` creates a table of contents by extracting an article_html's
`h2`-headlines of the dpa-digitalwires format.

## Requirements

* [node.js](https://nodejs.org/en/download/)

## Setup

1. Install dependencies by calling `npm install` or `yarn`
2. Call `node table_of_contents.js`. This will save the article and a table of contents with links to `table_of_contents.html`.
