# Notes 🔎

Bytes, memory, etc.

## TABLE OF CONTENTS

- [bytes](#bytes)

## Bytes

Your computer’s memory is like a postal address. Every mailbox has a postal address. That’s how your Mac, PC or phone work. You have memory, but you can think of it as individual mailboxes. You can put anything you want in those mailboxes. You can go TO a mailbox to get information from it. That’s what your computer is doing with info - organizing it. Organizing it into bytes.

A bit is a zero or a one. Think of a bit as like a lightbulb. If you are a computer and you want to represent the number 0, keep the light bulb off. If you want to represent the number 1, turn the light bulb on. Why is this relevant to computers? We are charging our laptops and phones, right? Physical resource being replenished whether a battery or a charger. Inside of a computer are millions of tiny switches (metaphorically as lightbulbs) and these are called transistors, or switches. They can either be flipped on (to represent 1) or flipped off to represent zeros. From that very simple mechanism -- electricty is there, or it is not - 1 or 1 - computers can count from 0 to 1, or higher, with more electricity. Computer wants to represent zero, it leaves light off. Wants to represent 1, switch the lightbulb on. How do we count out higher? More lightbulbs? Base-2 is binary. Base-10 is decimal. Think of 123. Right most number is in the 1s please, 2 is in the 10s please, 1 is in the 100s place. 100 + 20 + 3 = 123. Computers just have electricity, on or off, so we have to use base 2. 8 bits are in a byte. In real terms, videos or photographs are measured in bytes - kilobytes for thousands of bytes, megabytes for millions of bytes, gigabytes for billions of bytes (for video) that just means you have a lot of patterns of 8 bits, some cominbation of 0s and 1s on your computer's hard drive. A byte of bits is how a computer represents 0.

In units of 8 - in units of bytes, your computer.

ASCII - acronomym describing a mapping betwee numbers and letters. Not as simple as 0 1 2. 65 is A. 65 in binary is 100000001. 2s place is on the far right. ASCII historically used 7 bits to represent letters ( rounded to a byte) then ASCII can represent 256 total characters. That is fine for english but not for most languages. So, use more bits. Solution to ASCII is Unicode. Unicode is just a mappin of numbers to letters.

How do images get represented in computers? There is an assembly of RGB - red, green, blue. For every dot on your phone, TV or computer, there is a number represetning how much red, green and blue it should show. If a dot on your screen uses 72 73 33 (or bytes) medium red, medium green, a little bit of blue. Each of these are bytes - smallest value you can have in a byte is 0, largest value you can have in a byte is 255.

These 3 colors combine to a murky shade of yellow/brown. This is how a computer stores precisely this color. Zoom into an emoji, what do you see? Pixels. A dot on your screen is really just a pixel. Each dot on the screen is 3 bytes. A number represents every dot on the screen, so this is why images get so big.

How do you get video if at the end of the day all you get is zeros and ones? Pixels changing values over time. Or a sequence of images that over time change on the screen. 24FPS is 24
