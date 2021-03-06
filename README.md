Sample extensions
=======

These samples demonstrate techniques for building an extension with an HTML5 UI and behavior implemented in JavaScript. 

Many of the samples are still in development. Some of them use CEP 4 and the CC2013 version of the host app, others are for CEP 5 and CC2014 version of the host application and others are kept up to date with the latest release e.g. CC2015. You can check the manifest.xml file for each extension's compatibility requirements. To run the extensions you must have the host application installed. Requirements for each sample are listed below.


* Supported host apps for CEP 6 include the CC2015 versions of: Dreamweaver, Flash Pro, InDesign, Illustrator, InCopy, Photoshop, Premiere Pro, Prelude, and After Effects. 
* Supported host apps for CEP 5 include the CC2014 versions of: Dreamweaver, Flash Pro, InDesign, Illustrator, InCopy, Photoshop, Premiere Pro, Prelude, and After Effects. 
* Support for the Flash/ActionScript extension model is deprecated in all apps, and has been removed from Photoshop CC2014, Flash CC2015 and Dreamweaver CC2015.
 
From CEP 7.0, we post official CEP sample extensions under CEP-Resources, along with documentation, API, etc.
* [CEP 7.0 Sample Extensions](https://github.com/Adobe-CEP/CEP-Resources/tree/master/CEP_7.x/Samples)


##Before running the samples
The samples provided are unsigned so this will cause the the signature check (built into CEP when first running an extension) to fail. To bypass the signature check, please refer to the documentation:

* [CEP 7.0](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_7.x/CEP_7.0_HTML_Extension_Cookbook.pdf)
* [CEP 6.1](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_6.x/CEP_6.1_HTML_Extension_Cookbook.pdf)
* [CEP 6](https://github.com/Adobe-CEP/CEP-Resources/wiki/CEP-6-HTML-Extension-Cookbook-for-CC-2015#development_debugging)
* [CEP 5](https://github.com/Adobe-CEP/CEP-Resources/wiki/CEP-5-HTML-Extension-Cookbook-for-CC-2014#development_debugging) 
* [CEP 4](https://a248.e.akamai.net/f/1953/8974/2h/wwwimages.adobe.com/www.adobe.com/content/dam/Adobe/en/devnet/cs-extension-builder/pdfs/CC_Extension_SDK.pdf) (Page 25) 

----
## Requirements

Remember that although these extensions are initially setup for a particular version of CEP, you can adjust the product version targeted by modifying the range inside the `HostList` element of the `CSXS/manifest.xml` file.

| Extension | Description | Supported Products |
| --- | ------ | --- |
| [AfterEffectsPanel](https://github.com/Adobe-CEP/Samples/tree/master/AfterEffectsPanel) | Demonstrates how to invoke After Effects ExtendScript, from within a CEP panel. | After Effects|
| [Anywhere Example Panel](https://github.com/Adobe-CEP/Samples/tree/master/AnywhereExamplePanel) | Demonstrates a Premiere Pro panel integration with Adobe Anywhere (through DOM and http). | Premiere Pro, Prelude |
| [Audition](https://github.com/Adobe-CEP/Samples/tree/master/Audition) | There are 4 Audition CC extensions in this repo (ApplicationCommands, PlayheadPanel, ScriptDictionary, TransportEvents) | Audition |
| [Bridge - HelloBridge](https://github.com/Adobe-CEP/Samples/tree/master/Bridge/HelloBridge) | A Hello World extension for Adobe Bridge. | Bridge |
| [Bridge - ShowFolder](https://github.com/Adobe-CEP/Samples/tree/master/Bridge/ShowFolder) | Demonstrates use of CEP APIs and ExtendScript in Adobe Bridge | Bridge |
| [CEP HTML Invisible Extension](https://github.com/Adobe-CEP/Samples/tree/master/CEP_HTML_Invisible_Extension) | An example of an invisible extension. More information about invisible extensions can be found in the cookbooks https://github.com/Adobe-CEP/CEP-Resources/wiki/CEP-5-HTML-Extension-Cookbook-for-CC-2014#invisible | Dreamweaver, Animate, InDesign, InCopy, Illustrator, Photoshop, Premier Pro, Prelude, After Effects |
| [CEP HTML Test Extension](https://github.com/Adobe-CEP/Samples/tree/master/CEP_HTML_Test_Extension) | Showcases most features and capabilities of CEP 6, including events, video, database interaction via Node, native APIs, ExternalObject, HTML FlyOut menus and lots of other good stuff! | Dreamweaver, Animate, InDesign, InCopy, Illustrator, Photoshop, Premier Pro, Prelude, After Effects |
| [CueSheeter](https://github.com/Adobe-CEP/Samples/tree/master/CueSheeter) | Demonstrates extracting usage data from sequences; useful for documenting usage and clearance rights. | Premier Pro |
| [Flickr](https://github.com/Adobe-CEP/Samples/tree/master/Flickr) | Demonstrates connecting and retrieving assets from a Cloud service (Flickr in this case). | Photoshop |
| [htmlStandAlone](https://github.com/Adobe-CEP/Samples/tree/master/htmlStandAlone) | Demonstrates Prelude's message-driven Javascript APIs. Inside the sample, there are multiple standalone html pages that include demos for different ExtendScript functionalities you can use in Prelude. | Prelude |
| [Photoshop Events](https://github.com/Adobe-CEP/Samples/tree/master/PhotoshopEvents) | Demonstrates listening to events in Photoshop. | Photoshop |
| [Premiere Pro Panel](https://github.com/Adobe-CEP/Samples/tree/master/PProPanel) | Demonstrates a Premiere Pro panel. | Premiere Pro |
| [RSSReader](https://github.com/Adobe-CEP/Samples/tree/master/RSSReader) | Demonstrates using 3rd party NPM modules in a CEP 5 extension. | InDesign/InCopy, Illustrator, Photoshop |
| [SimpleDissolve](https://github.com/Adobe-CEP/Samples/tree/master/simpledissolve) | | Photoshop |
| [Trello](https://github.com/Adobe-CEP/Samples/tree/master/Trello) | Demonstrates loading an external website in an iFrame. | Photoshop, Illustrator, Premiere Pro |
| [TypeScript](https://github.com/Adobe-CEP/Samples/tree/master/Trello) | Demonstrates multiple sample codes thata demonstrate what's possible to build inside Premiere Pro. | Premiere Pro |
| [UI Showcase](https://github.com/Adobe-CEP/Samples/tree/master/UI_Showcase) | Demonstrates using common JavaScript UI frameworks in CEP extensions. | Photoshop, Illustrator, Premiere Pro |
| [WebGL with three.js (Contributed by Davide Deraedt)](https://github.com/Adobe-CEP/Samples/tree/master/webgl_threejs) | Demonstrates WebGL with `three.js` | Photoshop |
| [Websockets](https://github.com/Adobe-CEP/Samples/tree/master/Websocket) | Demonstrates using web sockets in an extension. | Photoshop, Illustrator, Premiere Pro |
| [XMP Sample Panel](https://github.com/Adobe-CEP/Samples/tree/master/XmpSamplePanel) | Demonstrates manipulating XMP metadata in CC2014 hosts. | Premiere Pro, InDesign, Photoshop, Illustrator |

