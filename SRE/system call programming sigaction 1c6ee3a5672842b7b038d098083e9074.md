# system call programming sigaction

```jsx
sigaction(SIGHUP, &newact, &oldact);
```

SIGHUP → signal type

newact → sigaction struct, 

the first element is the **sa_handler** and it can be SIG_IGN(ignore) or SIG_DFL(default), 

second the **sa_mask** that’s a set of signal to be blocked during execution of handler

third the sa_flags, which is the optional flask as like SA_RESTART

oldact → where return the old handler info (NULL if not interested)

![Untitled](system%20call%20programming%20sigaction%201c6ee3a5672842b7b038d098083e9074/Untitled.png)

we initialize a sigset by **sigemptyset(&s)**  which will clear all the bits

use **sigaddset(&s, SIGTERM)** to set the bit corresponding to one specific signal, and we can call multiple times to have multiple signals 

**sigdelset** **(&s, SIGTERM)**to delet a signal

**sigfillset(&s)** to set all bits them all

**sigismember(&s, SIGTERM)** to verify if this signal is in the sigset or not

![Untitled](system%20call%20programming%20sigaction%201c6ee3a5672842b7b038d098083e9074/Untitled%201.png)

> `history | grep ssh` or `Ctrl+R`
> 

```jsx

```