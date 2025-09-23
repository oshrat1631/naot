# Nikud Images Mapping

This folder contains the PNG images for Hebrew nikud characters used in the Montessori application.

## File Structure

Each nikud character corresponds to a specific PNG file:

| Character | Unicode | Hebrew Name | File Name | Base64 Image (order provided) |
|-----------|---------|-------------|-----------|--------------------------------|
| ַ | U+05B7 | Patah (פתח) | patah.png | 1st base64 string |
| ָ | U+05B8 | Qamats (קמץ) | qamats.png | 2nd base64 string |
| ֶ | U+05B6 | Segol (סגול) | segol.png | 3rd base64 string |
| ֵ | U+05B5 | Tsere (צירי) | tsere.png | 4th base64 string |
| ִ | U+05B4 | Hiriq (חיריק) | hiriq.png | 5th base64 string |
| ֻ | U+05BB | Qubuts (קובוץ) | qubuts.png | 6th base64 string |
| ְ | U+05B0 | Sheva (שווא) | sheva.png | 7th base64 string |
| ֲ | U+05B2 | Hataf Patah (חטף פתח) | hataf-patah.png | 8th base64 string |
| ֱ | U+05B1 | Hataf Segol (חטף סגול) | hataf-segol.png | 9th base64 string |
| ֳ | U+05B3 | Hataf Qamats (חטף קמץ) | hataf-qamats.png | 10th base64 string |

## Instructions

To complete the setup:

1. Take each base64 string from your original message (in order)
2. Decode it to a PNG file
3. Save it with the corresponding filename in this folder
4. The HTML will automatically load these images

## Base64 Strings (in order)

1. **patah.png**: data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAWcAAAC0CAYAAABIZe24AAAJ4UlEQVR42u3df2yU9R3A8c/d1Za2wgQphS2ZFEhkEUW3LIaxjIAxUf8xlpgxHIu/wPnzHwy4+BOmA2EbZouQ4QBlkQHGuD/UMGMImGgG/uOSxhjFFLMFWlpYGAHaXvvc/tgOj4NCgbbX9V6vxJTY9p7vPd/ru9977ulzqVwulwsAhpS0XQAgzgCIM4A4AyDOAOIMgDgDiDMA4gyAOAOIMwDiDCDOAIgzgDgDIM4AiDOAOAMgzgDiDIA4A4gzAOIMgDgDiDMA4gwgzgCIM4A4AyDOAIgzgDgDIM4A4gyAOAOIMwDiDIA4A4gzAOIMIM4AiDOAOAMgzgCIM4A4AyDOAMNFhV1QvnK5XKRSKfe/H24nl8tFT09PpNPpSJLk1OdSqdSpbaTT6bLe31yYVC6Xy9kNiO2Fbysioru7O44cORLvv/9+7Ny5MzZWbDjja+9oa4zrrrsubrvttrjhhhvinU6nzUGshEfJbrfrmmuuidtuu0033HCDbrjhhrivs7OzgxkZOQpz585VY2Oj5syZo1mzZmlwcFB2u53s7Gw8Hg85OTkUFBSQl5dHfn4+Y8aMISsri+rqajo6Opg2bVpfJG3btq3P9+hd29atWyM/n5+fr6KiIoqLiykoKKCwsJDCwkKKiooYN24cOTk5OBwOHA6H0tPTdeTIkYOBQCA6Ozv7OlZpaam6u7v7PK6oqLDdrlfggg==

2. **qamats.png**: [2nd base64 string from your message]

3. **segol.png**: [3rd base64 string from your message]

... and so on for all 10 images.

## Benefits of This Approach

- ✅ **Cleaner HTML**: No embedded base64 data
- ✅ **Better Performance**: Images can be cached separately 
- ✅ **Easier Maintenance**: Images can be updated independently
- ✅ **Smaller File Size**: HTML file is much more manageable
- ✅ **Better Organization**: Clear separation between code and assets
- ✅ **Debugging**: Images can be viewed directly in browser/file system