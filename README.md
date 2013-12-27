R_CURL
=================

R_CURL is a small c project that implements cURL library for managing protocols.
cURL is a computer software project providing a library and command-line tool for transferring data using various protocols. The cURL project produces two products, libcurl and cURL. It was first released in 1997.

Usage
-------------
```C
#include "R_Curl.c"

int main(int argc, char* argv[])
{
   	printf("\n//=====Starting file downloading=====//\n");
	downloadFileWithNameFromUrl("data.dat","http://en.wikipedia.org/wiki/CURL");
}
```

```BASH
$ gcc -lcurl main.c -o main
$ ./main
```

License
--------

This code is under the BSD license.
