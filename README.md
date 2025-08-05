
# fxmanifest Generator for FiveM

## Author

**Sunli**  

This is a simple web tool that lets you automatically generate a fxmanifest.lua file from a list of map and mod files for FiveM (.ymap, .ytyp, .ydr, .ytd, etc.).

## What is it for?

When creating a map or mod for FiveM, you need a fxmanifest.lua file listing all the files used and configuring the resource. This tool helps you easily generate that manifest by pasting your file list and generating the manifest automatically.

## How to use?

Open the generator web page (can be on GitHub Pages or locally).

Paste the list of files you want to include, one per line, for example:

```
rdd_main.ymap
rdd_big_rocks.ybn
rdd_main.ytyp
```

Click the Generate fxmanifest.lua button.

The generated content will appear in the output box.

You can copy it or download it using the Download fxmanifest.lua button.

## Features

- Automatically detects .ytyp files to include the required data_file 'DLC_ITYP_REQUEST' lines.
- Generates a basic fxmanifest compatible with fx_version 'cerulean' and lua54.
- Simple and lightweight web interface, no installation required.

## Can I use it for any map?

Yes, as long as your files are correctly listed and placed inside the stream/ folder of your resource, the generated fxmanifest will be valid.

## License

This project is open source and free to use and modify.
