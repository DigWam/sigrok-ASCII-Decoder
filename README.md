# sigrok-ASCII-Decoder
Small extension to the existing SigRok Parallel Decoder to decode to ASCII characters

Drop the ASCII folder in your SigRok/PulseView decoders folder and restart the program, it should just work.

It is based on the existing parallel decoder, I've just added support to show printable 
ASCII charaters in place of the hex values. You can see the Hex too by setting the Data Wordsize
option to a value greater than zero. You can also select how the ASCII space is shown in the decode stream.

I created this because I had a use for it and it gave me an nice easy entry in to the world of
creating decoders for SigRok PulseView.

