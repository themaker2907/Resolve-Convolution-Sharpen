A resolve DCTL plugin designed for sharpening video using convolution sharpening. Ideal for sharpning the soft video seen with Canon DSLR cameras (such as the Canon 5D mark iii) to gain a more detailed, crispy, and unhaloed image - the latter artifact caused by sharpening edges using a unsharp filter.

I tried to look for ways to sharpen video just like how Premiere Pro did, but found out the ways that sharpening in resolve happens differently - all based off unsharp mask. Although this can increase sharpness by sharpening edges in video, it could result in halo artifacts similar to the in camera sharpening in Canon DSLRs - which looks very electronic, unnatural, and in general awful. During my research, I learned about convolution matrices as that is the sharpening in premiere pro - the "sharpen effect"  - works. 

This plugin only works with the studio version of resolve, as the free edition does not support DCTLs

There is alot of information about this in the wiki page, so please have a look
