## HRUN

    Usage: hrun [OPTIONS...] PROGRAM [ARGS...]
    
    This program helps executing programs for debugging. You can specify
    a different prefix, run it with GDB/VALGRIND/STRACE and add a breakpoint
    in a function.
    
    -g        : Run with GDB.
    -m        : Run with Valgrind (./valgrind.log)
    -s        : Run with strace.
    -v        : Show variables.
    -b FUNC   : Put a breakpoint in function.
    -p PREFIX : Run on prefix.


## HCCRUN

    Usage: hccrun [OPTS...] [C-FILE] [ARGS...]
    
    This program helps executing C files as scripts. In order to this to work
    start your scripts with `//bin/true && exec hccrun "hccrun" "$@"`
    and name it with the proper suffix (.c/.cc).
    
    You can put options for the compiler with `//hccrun/ldflags: -lpthread`.
    
    -v                : Show configuration.
    -i PROG PARAMS... : Do not execute, instead extract parameters.


## DONATIONS
<ul>
<li>
<a href="https://openvirtus.github.io/files/1C1ZzDje7vHhF23mxqfcACE8QD4nqxywiV.png">[QR]</a>
<img height="20" style="max-height:1em;max-width:1em" src="https://openvirtus.github.io/files/btc-logo.png">
Bitcoin <code>1C1ZzDje7vHhF23mxqfcACE8QD4nqxywiV</code>
</li>
<li>
<a href="https://openvirtus.github.io/files/bnb194ay2cy83jjp644hdz8vjgjxrj5nmmfkngfnul.png">[QR]</a>
<img height="20" style="max-height:1em;max-width:1em" src="https://openvirtus.github.io/files/bnb-logo.png">
Binance <code>bnb194ay2cy83jjp644hdz8vjgjxrj5nmmfkngfnul</code>
</li>
<li>
<a href="https://openvirtus.github.io/files/88JP1c94kDEbyddN4NGU574vwXHB6r3FqcFX9twmxBkGNSnf64c5wjE89YaRVUk7vBbdnecWSXJmRhFWUcLcXUTFJVddZti.png">[QR]</a>
<img height="20" style="max-height:1em;max-width:1em" src="https://openvirtus.github.io/files/xmr-logo.png">
Monero <code>88JP1c94kDEbyddN4NGU574vwXHB6r3FqcFX9twmxBkGNSnf64c5wjE89YaRVUk7vBbdnecWSXJmRhFWUcLcXUTFJVddZti</code>
</li>
</ul>
