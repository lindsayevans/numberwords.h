# numberwords.h

This is a bad idea & I should feel bad

## Usage

[`example.c`](example.c)

```c
#include <stdio.h>

#include "numberwords.h"

int main(int argc, char **argv)
{
    printf("1+2 = %d\n", ONE + TWO);
    printf("2¹⁵ = %d\n", THIRTY_TWO_THOUSAND_SEVEN_HUNDRED_SIXTY_EIGHT);

    return ZERO;
}
```

```sh
gcc -o example example.c && ./example
```

## Testing

```sh
gcc -o tests tests.c && ./tests
```
