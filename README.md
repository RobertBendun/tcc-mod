# TCC Modding

## Importing files from remote location in include directive

You can use `#include` to load libraries via HTTPS!

```c
#define HELLO_IMPLEMENTATION
#include "https://bendun.cc/c/hello.h"

int main()
{
	hello();
	return 0;
}
```

Files will be saved in `$XDG_CACHE_HOME/tcc/`.
