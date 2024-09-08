# kicad_library
This repository contains the KiCad libraries that I use for my projects. The libraries are a mix of my own libraries and libraries from other sources. The libraries are provided as is and I do not guarantee that they are error free. Use at your own risk.

## How to use
The library consists of two folders, footprints and symbols. To use this library, clone the repo, open KiCad and add the libraries to the global library table. Use the folder button to bulk add the libraries.

The library setup is based on Altium365. In the library_info.txt document, all symbols and footprints are shown with their corresponding LCSC number. This file is specifically useful when selecting footprints in Kicad.

## How I created the library
Most footprints are from EasyEda/LCSC, where I created my own GUI to add them to the library based on JLC2KicadLib. The GUI will be published soon.

## library_info.txt
The library_info.txt file contains all the footprints and symbols in the library. The file is structured as follows:
```txt
Library: <library_name>
    Symbol: <symbol_name> 
    Footprint: <footprint_name>
    LCSC_ID: <LCSC_number>
    
Library: <library_name>
    Symbol: <symbol_name> 
    Footprint: <footprint_name>
    LCSC_ID: <LCSC_number>
```
The file is structured in this way to make it easy to search for a specific symbol or footprint.