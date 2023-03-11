# Pico CTF Forensics Writeup

## informatioon (Forensics) | [Write Up](https://reversingfun.com/posts/picoctf-2021-forensics/)

1. Download imag
2. Use tool such as exiftool or 29a.ch/photo-forensics/ to extract image metadata
3. In the metadata, you will find licencse tag. Copy the string
4. Dump the tag into [cyberchef](https://gchq.github.io/CyberChef/) . You will learn that the tag is base64
5. Convert to CTF tag and done.

## Information Image

![image](/images/picoctf/information_image_metadata.png)

## Matryoshka doll (Forensics)

1. DL image
2. Use forensic tool or commands such as `hexdump -C {location of the image} | less +/"ff d9"` to see string information
3. See any relevant image file inthe string
4. try `unzip {imaage file}`
5. Continue the process and done
