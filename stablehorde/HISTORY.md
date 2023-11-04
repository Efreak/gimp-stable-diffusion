# History
## GIMP Plugin
### 1.3.7
Bugfixes
- Added support to choose model to generate new imaage, image to aimage, and inpainting.

## GIMP Plugin
### 1.3.5
Bugfixes
- In some cases generation failed due to invalid prompt strength values

### 1.3.4
Changes
- The generated images are now transferred via Cloudflare r2.

### 1.3.3
Changes
- The new parameter r2 is transferred with value False. This disables for now the new Cloudflare r2 image download.

### 1.3.2
Changes
- Now detailed error messages are displayed. Before only the standard HTTP error messages.

### 1.3.1
Changes
- In the case no worker is available for image generation, now a message is displayed.
- Minimum size has been reduced from 512x512 to 384x384.
 
### 1.3.0
Changes
- Inpainting is supported now

### 1.2.0
Changes
- Now images with sizes between 512x512 and 1024x1024 can be generated. Before only 512x512.

### 1.1.0
Changes
- img2img is now supported.

### 1.0.2
Changes
- If a new version of the plugin exists, a message is now displayed.

### 1.0.1
Changes
- NSWF toggle added. If you want to use an explicitly NSWF prompt, you can flag the request now accordingly.

### 1.0.0
Initial version
