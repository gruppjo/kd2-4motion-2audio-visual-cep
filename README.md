# Audio Visual CEP
Audio Visual CEP Extension that runs in after effects v.17.

## Versions
- v0.1.2
  - fix typo in file path
- v0.1.1
  - add a white background
- v0.1.0
  - successful boilerplate
  - loads an image from `~/Downloads/myFile.jpg`

## Development Journey
- Resources
  - Getting Started Guide [GitHub Adobe-CEP](https://github.com/Adobe-CEP/Getting-Started-guides)
  - CEP 9.x Documentation [GitHub Adobe-CEP/CEP-Resources](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/Documentation/CEP%209.0%20HTML%20Extension%20Cookbook.md)
  - `CSInterface.js` for [CEP_9.x](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/CSInterface.js)
    - Version, RunTime, Extension, CSEvent, SystemPath, ColorType, RGBColor, Direction, GradientStop, GradientColor, UIColor, AppSkinInfo, HostEnvironment, HostCapabilities, APIVersion, MenuItemStatus, ContextMenuItemStatus, CSInterface
    - THEME_COLOR_CHANGED_EVENT
    - [getHostEnvironment()](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/CSInterface.js#L487)
    - loadBinAsync(), loadBinSync(), closeExtension(), getSystemPath()
    - [evalScript()](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/CSInterface.js#L612)
    - [getApplicationId()](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/CSInterface.js#L627)
    - [getHostCapabilities()](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/CSInterface.js#L639)
    - [dispatchEvent()](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/CSInterface.js#L651)
    - [addEventListener()](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/CSInterface.js#L672), removeEventListener
    - [requestOpenExtension()](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/CSInterface.js#L701)
    - [getExtensions()](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/CSInterface.js#L716)
    - [getNetworkPreferences()](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/CSInterface.js#L730)
    - [initResourceBundle()](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/CSInterface.js#L754)
    - [dumpInstallationInfo()](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/CSInterface.js#L792)
    - [getOSInformation()](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/CSInterface.js#L805)
    - [openUrlInDefaultBrowser()](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/CSInterface.js#L896)
    - [getExtensionId()](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/CSInterface.js#L908)
    - [getScaleFactor()](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/CSInterface.js#L927)
    - [getCurrentApiVersion()](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/CSInterface.js#L968)
    - [setPanelFlyoutMenu()](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/CSInterface.js#L1001), updatePanelMenuItem, setContextMenu
    - [registerInvalidCertificateCallback()](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/CSInterface.js#L1216)
    - [registerKeyEventsInterest()](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/CSInterface.js#L1262)
    - [setWindowTitle()](https://github.com/Adobe-CEP/CEP-Resources/blob/master/CEP_9.x/CSInterface.js#L1275), getWindowTitle()
