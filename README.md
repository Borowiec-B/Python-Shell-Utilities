# Python-Shell-Utilities
My personal system of convenient usage of Python functions from Shell.

Consists of three layers:
 - Regular Python code
 - Python-to-Shell adapters (wrappers for first layer, taking argv-like arguments and communicating with Shell through shell.py's functions)
 - Dispatcher finding and calling the correct adapter (call_wrapper.py is the entry point of it all, called from Shell)
