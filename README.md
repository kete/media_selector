# media_selector

## Description

A jQuery and Sammy.js based mini-application for choosing from a list of providers' media assets (images, audio, video, etc.). Uses OpenSearch and oEmbed so that it can be easily plugged into services that provide those standards.

## Installation

media_selector is meant as a building block for things like an image chooser in a WYSIWYG rich text editor, like TinyMCE. However, it can be used standalone as long as you set up media_selector/data/providers.json appropriately to point at a provider(s) that answers OpenSearch and oEmbed requests.

To set up, copy data/providers.json.example to data/providers.json and edit to suit.

## Usage

See https://github.com/kete/image_selector_tinymce_plugin for how it can be configured to be used with a Rich Text Editor.

## Dependencies

jQuery (through a link to Google's CDN), Handlebars.js (through a link to cdnjs CDN), and Sammy.js along with some Sammy.js plugins that are included in the javascripts directory.

## Author

media_selector was created for the Kete project (http://kete.net.nz) and is maintained by Walter McGinnis <walter a-t katipo dot co dot nz>.

## License

media_selector is covered by the MIT License. See LICENSE for more information.
