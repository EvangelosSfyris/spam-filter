# spam-filter
/* Author: Evangelos Sfyris
*
*  Description: This program offers an interface with four commands: load, display, check, and filter.
*  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
*
*  Load takes fills a vector with a file of known spam emails, required to be sorted in alphabetical order.
*  
*  Display simply prints out each address contained within.
*  
*  Check takes a single email input by user and binary searches the vector to see if that email is spam.
*  
*  Filter, using a vector loaded with known spam addresses, will read in a file of various email addresses
*  and print the real ones to the file specified by the user.
*  This command, which uses Check, is of O(N*logN) complexity.
* 
*/
