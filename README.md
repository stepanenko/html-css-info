
# HTML and CSS Notes

[Code Beautify](https://codebeautify.org/) - Code Formatter, JSON Beautifier, XML Viewer, Hex Converters and more...

REM to PX Converter - https://codebeautify.org/rem-to-px-converter

## CSS

### Absolute Units

**PX**: Pixels (px) are considered absolute units, although they are relative to the DPI and resolution of the viewing device. But on the device itself, the PX unit is fixed and does not change based on any other element. Using PX can be problematic for responsive sites, but they are useful for maintaining consistent sizing for some elements. If you have elements that should not be resized, then using PX is a good choice.

### Relative Units

**EM**: Relative to the parent element

**REM**: Relative to the root element (HTML tag)

**%**: Relative to the parent element

**VW**: Relative to the viewport’s width

**VH**: Relative to the viewport’s height

Unlike PX, relative units like %, EM, and REM are better suited to responsive design and also help meet accessibility standards. Relative units scale better on different devices because they can scale up and down according to another element’s size.
