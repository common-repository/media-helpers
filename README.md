wp-media-helper
===============

A Wordpress plugin that adds several helpers to the default WP Media Management.

### Description

This plugin adds several helpers to the default WP Media Management. Each helper tries to be as tiny as possible (as a feature and as lines of code) and independent from the other helpers. Helpers can be enabled one by one.The aim is to provide a fine control and to avoid all possible conflicts. 

 - Use an external URL as the media file and save it to the database like an uploaded media. This allow external media providers to be used inside the Media Library. You can also attach a new media to a post without specifying any file (fake media). This allows you to work on the media without having the file yet.
 - Duplicate media
 - Limit the resolution of uploaded images (WP allows you to limit the filesize, but not the resolution)
 - Update a media permalink each time its title is changed (now included in core for WP 3.5)
 - Change the parent of a previously attached media
 - Change the file of a media without creating a new media entry

### License

© Copyright 2013 Fabien Quatravaux

wp-media-helper is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

wp-media-helper is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with wp-media-helper.  If not, see <http://www.gnu.org/licenses/>

