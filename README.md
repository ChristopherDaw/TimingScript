# TimingScript
Zsh script to time any command any number of times.

* After the script is finished, it will print out the total time elapsed and the average time.
* By default, the script runs the command 5 times.
* If an error is thrown by the command, the script exits.

## Usage

Skeleton:
```sh
 ./timingscript.sh [options] <command>
 ```

Example:

```sh
./timingscript.sh -r 30 python do-calculus.py integrals.json
```
