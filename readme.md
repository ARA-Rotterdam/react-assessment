This assesment is about your ability to see structure in data, and your skils to organize this data from a website into a renderable react component tree.

The file data.json contains dummy generated content from a Drupal 8 GQL query, and the assesment is to transform that data from the paragraphs structure into renderable tree of react components.
The layout property of single paragraph contains a json encoded string with metadata, and that paragraph entity can either be a layout row (1 to 4 columns) or the content of one of the names columns in of those rows.

The content of the data.json is one page, but every other page can contain different rows with different content paragraphs. The only that is fixed is the structure of the entity node in the data.

The output doesn't need to be styled, but it should be rendered in a browser and it should be clear the content of a row is in the right row type and column so some basic css should be added.

