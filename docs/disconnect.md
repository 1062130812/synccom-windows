# Disconnect

###### Support
| Code | Version |
| ---- | ------- |
| synccom-windows | 1.0.0 |


## Disconnect
The Windows [`CloseHandle`](http://msdn.microsoft.com/en-us/library/windows/apps/ms724211.aspx) is used to disconnect from the port.


###### Examples
```c
#include <Windows.h>
...

CloseHandle(h);
```


### Additional Resources
- Complete example: [`examples/tutorial.c`](https://github.com/commtech/synccom-windows/blob/master/examples/tutorial/tutorial.c)