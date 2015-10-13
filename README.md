# imint.se
Website for imint.se

The site is built with [Hugo](http://gohugo.io/) and deployed to Github Pages.

Changes to the repository will trigger a [Wercker](http://wercker.com/) script that builds and deploys the site automatically.

## Editing
#### Markdown
The main content is placed in the content folder into markdown files.
There are templates for different content types called archetypes, to use them run ```hugo new path/to/file/my-new-file.md --kind="archetype-to-use"```.
#### Other Content
Images and other content is placed in static. Create folders corresponding to the path and the name of the content file they belong to and place the files there.

## To run this site on a local computer follow these steps

1. Clone the repository to your computer with ```git clone https://github.com/imintsystems/imint.se --recursive```.
2. If Hugo is not installed go to https://github.com/spf13/hugo/releases and download the latest release. (v0.14 was used to build this site)
3. Stand in the root folder of the cloned repository and run ```hugo server -w -t hugo-vidhance-theme``` to start a local webserver hosting the site and that refreshes the site when a file is edited.
