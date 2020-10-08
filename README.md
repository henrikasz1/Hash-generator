# Hash-generator

:hash: It is a simple program, which generates unique hash code of any size of text :hash:

The hash function complies all the requirements that were specified in the given task:
* Input can be of any size  :heavy_check_mark:
* Output will always be in fixed length  :heavy_check_mark:
* Hash function is deterministic (output of the same input is also the same)  :heavy_check_mark:
* Hash function is fast  :heavy_check_mark:
* It is impossible to recover text from a hash code  :heavy_check_mark:
* Hash function is collision resistant  :heavy_check_mark:

This is how hash function works: :snail:

* Converting text into binary code
* Padding the binary code, so that it will be divisible by 256
* Using logic gates to mix all the binary code (makes hash code irrecoverable)
* Converting binary to hexadecimal code
