# 1024-Bits-Basic-Calculator
* Its a calculator for the numbers upto 1024 bits capacity.
* It can add, subtract and multiply and displays only if result is in range of 1024 bit.
## Description
* It checks and informs if the numbers are in range or not.
* It also checks after addition and multiplication whether its under range or not.
* As we know 1024 bit so we are trying to convert it into base 10 which can max contain log(2^1024) which is 308 digits max and 1 charector for '\0' charector so max 309 is the length
## Idea used
* So given Input is stored in an string string in the bigint user defined data type along with size.
* When ever it has 308 input charactors we check whether the number is greater than 2^1024-1 or not.
* After multiplication again its chcked whether it is in range of 1024 bit or not.
## Assumptions
* The numbers are always positive.
* The input doesn't contain 0's before the input.
