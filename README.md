# Firefox Deployment Example

Customized deployment options for Mozilla Firefox. The goal is primarily to supply good defaults in addition to the boring stuff like bookmarks. uBlock Origin is also included by default. This is all handled using [distribution.ini](Mozilla%20Firefox/distribution/distribution.ini) and the [extensions directory](Mozilla%20Firefox/distribution/extensions).

## Installation

The contents of the "Mozilla Firefox" directory should be copied to the Firefox application directory. It will be "C:\Program Files\Mozilla Firefox", or "C:\Program Files (x86)\Mozilla Firefox".

## Adding Extensions

To add an extension to the extensions directory:

1. Download the latest version from Mozilla Addons. 
2. Rename the xpi file to the extension's ID. You can find the extension ID by extracting the XPI (it's a zip file) and finding "id" in manifest.json.
	* Example: uBlock's id is ``uBlock0@raymondhill.net``.