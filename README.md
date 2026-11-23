# Deleted but Not Gone

A Python terminal simulator for a class presentation on digital footprints. It uses a fictional photo and illustrative retention rules. The rules do not represent any company's policy.

## Run locally

With Python 3 installed, open a terminal in the folder containing the script and run:

```sh
python digital_footprint_simulator.py
```

If your system uses `python3` or `py`, substitute that for `python`. The script uses only Python's standard library.

## Class demo

1. Type `upload`. Ask the class which copies they expect to disappear when you delete the post.
2. Type `delete`. The profile photo becomes hidden, and all four copies are still stored.
3. Type `advance 1`, then `advance 7`, then `advance 30`. Watch the cache, server, and backup copies expire.
4. Type `clear saved`. This simulates the other person removing the copy from their device.
5. Type `reset` to replay, `help` to see all commands, or `quit` to exit.
