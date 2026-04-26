Hasselblad Baseline Exposure - this Darktable lua script reads the baselineExposure (0xC62A SRATIONAL) directly from the 3FR binary and adds it (via a button) to the default exposure. This is necessary for images that are taken using HDR mode in the X2DII, as they show underexposure when imported into Darktable.

Leica Q3 Digital Zoom - this Darktable lua script reads the .dng file for "in camera" digital zoom (crop) and applies it (via a button).

OpenInApp - Opens selected raw files in a configured external application (e.g. Iridient Developer). When you quit the external app, the plugin automatically detects any new .tif files saved alongside the originals and imports them into your Lightroom catalog.
