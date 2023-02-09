- Binary and hexadecimal numbers systems underpin the way modern computer systems work. Low-level interactions with hexadecimal (hex) and binary are uncommon in the world of Java programming, but software developers do occasionally operate at the bit and byte level. The ability to understand how these alternate number systems work is an important skill for a well-rounded software developer to have.
- Working in hex or binary can feel strange and confusing compared with the base 10 number system used in our everyday world.
- It's not rocket science, but it requires adjusting how one thinks about numbers and numerals. The following binary and hexadecimal examples explain how these alternatives to the decimal-based number system function and behave.

*The Base 10 Number System*

- Let's begin to understand binary and hexadecimal number systems with a real-world example.

- Consider the numeral 500. In a number system, each digit represents a power of the base. For the base 10 number system, each digit represents a power of 10. Here's how base 10 describes the numeral 500:

hundreds | tens | ones
-------- | ---- | -----
10² | 10¹ | 10⁰
5 | 0 | 0

- In the table above, the leftmost column describes units of 100 (10²), the middle column describes units of 10 (10¹) and the rightmost column describes units of one (10⁰). Thus, we can express the value of 500 in base 10 as five units of 100, zero units of 10 and zero units of one, all added together.

*Binary vs. base 10*

- Base 10 is great for humans, but -- for reasons dealing with the on and off energy states -- computers use a base 2 number system. With base 2, or binary, every digit represents a power of 2 and digits are described as only two numbers: 0 and 1. The table below shows the binary-to-decimal-conversion of the value of 500:

Exponent values expressed in decimal | 256 | 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 
------------------------------------ | --- | --- | -- | -- | -- | - | - | - | - 
|                                    | 2⁸ | 2⁷ | 2⁶ | 2⁵ | 2⁴ | 2³ | 2² | 2¹ | 2⁰
|                                    | 1 | 1 | 1 | 1 | 1 | 0 | 1 | 0 | 0 

**(Note: a unit of 20 = 1)**

- Thus, 500₁₀ = 111110100₂. Or, on a digit by digit basis in base 2: 500 = (256 + 128 + 64 + 32 + 16 + 0 + 4 + 0 + 0)

- There are two more rules to calculate numbers in the binary system. First, in the world of digital computing, each digit in a base 2 number is called a bit. Thus, the following numerals represent three-bit values: 000, 001, 011, 100, 101, 110 and 111. Similarly, eight digits are eight-bit values, such as 10101010, along with 11110000 and 11111111
- Secondly, bits are grouped together into an organizational unit called a byte. Typically, a byte is a group of eight bits, such as the number 10101010. Grouping eight bits into a byte is conventional, although some technologies such as Protocol Buffers organize a byte as a seven-bit group.
- Working with bits and bytes using binary notation can be hard just at the visual level alone. Consider the binary expression 1001001011011001 -- that long of a number is hard for anyone's brain to decipher

*Hexadecimal vs. Binary*

- Binary numbers can be intimidatingly long, but hexadecimals are the exact opposite. Hexadecimal numbers describe a number in fewer numbers than both binary and the base 10 number system.
- The first thing to understand about the hexadecimal system is that it is made up of sixteen numerals: 0 1 2 3 4 5 6 7 8 9 a b c d e f
- In any number system, each digit represents a power of the base. In the base 10 (decimal) system, the numeral 10 represents one unit of 10¹ and zero units of 10⁰. In the hexadecimal system, the numeral 10 represents a power of the number 16, as shown in the table below:

Exponent values expressed in decimal | 65536 | 4096 | 256 | 16 | 1
------------------------------------ | ----- | ---- | --- | -- | - 
|                                    | 16⁴   | 16³  | 16² | 16¹ | 16⁰

- Thus, the decimal 10 describes a value of 10 in base 10, while in hexadecimals the numeral 10 converts to 16. We can illustrate the conversion like so:

Exponent values expressed in decimal | 16 | 1
------------------------------------ | -- | - 
| | 16¹ | 16⁰
In hexadecimal | 1 | 0

*Decimal vs. hexadecimal*

- Those extra numeric symbols in hexadecimal -- a b c d e f -- help alleviate the confusion with translating decimals, such as numeral 10, into the base 16 number system. The table below describes the correlation of numerical symbols between decimal and hexadecimal.

decimal | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 
------- | - | - | - | - | - | - | - | - | - | -- | -- | -- | -- | -- | --
hexadecimal | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | a | b | c | d | e | f

- Thus, going back to the decimal example with 500, we can express it in hexadecimal notation as 1f4. The table below describes the logic behind this correlation:

Exponent values expressed in decimal | 256 | 16 | 1
------------------------------------ | --- | -- | -
| | 16² | 16¹ | 16⁰
In hexagonal | 1 | f | 4

- Let's take the example further, and convert each hexadecimal digit to its decimal equivalent and then add them:

(16² x 1) + (16¹ x 15) + (16⁰ x 4)

= (256 + 240 + 4)

= 500