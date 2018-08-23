# hamming-code-error-detection-and-correction
In communication system , information data that to be transferred from source to destination may be corrupted due to any type of noise. To find the original information, we use hamming code error detection and correction technique.
Here, we input 16 bit data and take 21 bit output hamming code by adding 5 parity bits to the input data.
And 21 bit hamming code with 1 bit error or 2 bits error or parity bit error is given to the system , then we get 16 bit output data which consists of message bits along with other output which intimates the type of error in the given 21 bit code.
If the error is single bit error then output data bits are changed accordingly and displayed.. If it is 2 bit error or parity bit error then data bits are displayed without any change in their message..
And check bits are also displayed so that we can find the position of the error bit in the case of a single bit error hamming code..
