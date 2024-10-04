# Steganography
### Steganography is a method of hiding secret data into Video, audio, payloads, txt files, image.
### In most cases we use an Image to deliver secret data embedded in It, We can deliver payload and bypass security but when u extract it payload maybe detect.
## This are tool we used for Steganography
## Quick-Stego (windows gui)
👉 [Quick-stego](https://github.com/Esther7171/steganography/raw/main/QS12Setup.zip)
## Steghide (cli both for win,linux)
👉 [Steghide](https://github.com/Esther7171/steganography/raw/main/steghide-0.5.1-win32.zip)

## Embedding Data into a File
```
steghide embed -cf [cover file] -ef [file to embed] -sf [stego file]
```
* ### Example
```
steghide embed -cf image.jpg -ef secret.txt -sf image_with_secret.jpg
```
## Extracting Data from a File
```
steghide extract -sf [stego file]
```
* ### Example
```
steghide extract -sf image_with_secret.jpg
```
