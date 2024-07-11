# Data storage

----
# Introduction
* Data today comes in diffrent forms including:
   * Numbers
   * Text
   * Image
   * Audio
   * Video
* All data types are transformed into a uniform representation
* Universal representation is called: 
   * bit pattern
   * Sequence of 0 and 1
* Bits \(binary digits\): Symbol 0 and 1 is called a bit, smallest unit of data can be stored in a computer
* Bits patterns: A sequence, string of bits. 8 bit = 1 byte
* Number is changed to binary system before being stored in the computer memory.
* Stored decimal point:
   * fixed-point
   * floating-point

----
# Unsigned Representation
* Can only >= 0
* 0 will be added to the left if number of bits less than n-bits
* EX: unsigned 7 stored in 8-bit is \(00000\)\(111\)
* Overflow in unsigned integers

----
# Sign and magnitude representation
* Unsign intergers \(0 -> 2n-1\) divide into 2 equal sub-range
   * First half: Positive intergers
   * Second half: Negative intergers
* 2 Diffrent ways to represent 0. 0 and -0
* Overflow positive and negative overflow

----
# Two's Complementing
* Original -> two complementing: bitwise + 1
* Smart ways: Copy bits from the right until 1 is copied, then flip the rest of the bit
* Used for changing positive -> negative numbers. \(will remove -0\)

----
# Storing reals
* Contain integral part and a faractional part
* Can used fixed-point representation to represent real number but it isn't accurate
* Floating point is more accurate
   * Divide in 3 part: a sign, a shifter and â fixed-point number
   * More complex, hard to calculate

----
# Storing Text
* Represent text by groups of bits, each pattern define a symbol
* Using ASCII, unicode

----
# Storing audio
* Audio is a representation of sound or music
* Is an example of analog data
* Stored by select only a finite number of point on analog signal

----
# Quantization
* Store 40000 real values for each one second sample
* refers to a process that rounds the value of a sample to the closest interger value

----
# Encode
* Bit rate is a number of bit per seconds
* Calculate: bit rate = bit depth \(number of bits\) x number of samples per seconds.

----
# Standarts for sound encoding
* MP3: MPEG Layer 3 ~ 44100 samples per seconds, 16 bits per sample
* 705,600 bits per seconds -> lossy compression, Oppose to lossless

----
# Storing image
* Raster graphic \(bitmap graphic\) -> stored an analog image
* Sampling in this case = scanning
* Sample = pixels
* Resolution: Scanning rate in image processing
* Color depth: number of bits used to represent a pixel
* True-color: used 24 bits to encode a pixel
* Indexed color

----
# Standart for image encoding
* JPEG \(Joint Photographic Expert Group\) used True-color Scheme, but compress the image to reduce the number of bits
* GIF \(Graphic Interchange Format\) used indexed color scheme
* Softwares: Photoshop, PhotoImpact, Corel Painter

----
# Vector Graphic
* Raster graphic has disadvantages:
   * Filesize is big
   * Rescaling
* Vector graphic does not stored the bits patterns for each pixel
* An image is decomposed into a combination of geometricala shape
* Standart for vector graphic: ESP, WMF, AI, CDR
* Software: Illustration, CorelDRAW, Flash

----
# Storing Videos
* Represented by multiple of image \(frames\) over time
