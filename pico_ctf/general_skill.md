# Pico CTF General Skill Writeup

## Obedient Cat

1. Download file
2. Open and you will see the flag
3. Done

## Nice netcat

1. Follow the guideline and run `nc mercury.picoctf.net 21135`
2. The terminal will return numbers. Copy and paste the number to tool such as [this tool](https://www.duplichecker.com/ascii-to-text.php)
3. Convert ASCII to text and should return flag.

## what's a net cat ?

1. Check the instruction and use nc command to get flag
2. Done

## First Grep

1. Install file
2. grep pico {filename}
3. Done

## Lets Warm Up (General Skills)

1. Use tool [like this](https://onlinehextools.com/convert-hex-to-ascii) to convert 0x70 to ASCII and done.

## Wave a Flag (General Skill) | [Write Up](https://ctftime.org/writeup/28150)

1. Donwload the executable file
2. Try to run the file from terminal but you will notice the file has permission issue
3. chmoe +x {file name} to make the file executable
4. ./{filename} to execute
5. it will ask you to add `-h` at the end
6. add and get the ctf

*Current Laptop is ARM64 while the executable file is for AMD64, which is not compatible. You need to use thing such as a docker to execute the file.

## Static ain't always noise

1. Run the bash script with the static file.
2. grep CTF related text to find the answer.

