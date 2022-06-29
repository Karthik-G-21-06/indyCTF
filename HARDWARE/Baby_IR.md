# Baby_IR
## description
An IR Communication was sniffed between two people. The data was a pile of binary digits. Analyze the data sniffed and use them in the circuit and get a "meaning full" flag. (Data contains junk values too.)
```
1.111111010101000010101111

2.111111011001010001111111

3.111111010000100011110111

4.000111011001010001111111

5.111111011011000001001111

6.010111001001010001110111

7.111111010001100011100111

8.010111001011010101110011

9.111111011000000001111111
```
## attachment
click [here](https://www.tinkercad.com/things/4slF5jEpkEQ-copy-of-sniffcomm/editel?tenant=circuits)

## How I did it
Some binary digits where given. I just analysed the code for arduino and saw that the flag was a combination of hexadecimal values. So just converted the binary to hexa and made a sting combining them in the order and got the flag.

## Flag
the flag is: ictf{whrs_m4_flaG}