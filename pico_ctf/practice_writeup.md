# Pico CTF Practice Writeup

1. Obedient Cat (General Skill)

```text
1. Download file
2. Open and you will see the flag
3. Done
```

2. Mod26 (Cryptography)

```text

1. Copy the encrypted text 
2. Access rot13.com and paste the text for decipher
3. Done

```

*Informatioon (Forensics) | [Write Up](https://reversingfun.com/posts/picoctf-2021-forensics/)

```Text

1. Download imag
2. Use tool such as exiftool or 29a.ch/photo-forensics/ to extract image metadata
3. In the metadata, you will find licencse tag. Copy the string
4. Dump the tag into cyberchef gchq.github.io/CyberChef/ . You will learn that the tag is base64
5. Convert to CTF tag and done.

```

3. Information Image
![image](/images/picoctf/information_image_metadata.png)

*Wave a Flag (General Skill) | [Write Up](https://ctftime.org/writeup/28150)

```Text

1. Donwload the executable file
2. Try to run the file from terminal but you will notice the file has permission issue
3. chmoe +x {file name} to make the file executable
4. ./{filename} to execute 
5. it will ask you to add `-h` at the end
6. add and get the ctf

*Current Laptop is ARM64 while the executable file is for AMD64, which is not compatible. You need to use thing such as a docker to execute the file.

```

4. Nice netcat... (General Skills)

```Text

1. Follow the guideline and run `nc mercury.picoctf.net 21135`
2. The terminal will return numbers. Copy and paste the number to tool such as duplichecker.com/ascii-to-text.php
3. Convert ASCII to text and should return flag.

```

5. what's a net cat ? (General Skills)

```Text

1. Check the instruction and use nc command to get flag
2. Done

```