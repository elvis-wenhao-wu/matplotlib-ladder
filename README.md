# matplotlib-ladder

Explanations of Matplotlib Concepts in a Cascaded Style

Meta Info

- Version: `matplotlib.__version__`

- Installation Location: `matplotlib.__file__`

- Configuration and Cache Directory Locations: 

    - `matplotlib.get_configdir()`
    - `matplotlib.get_cachedir()`

    If you would like to use a different configuration directory, you can do so by specifying the location in your `MPLCONFIGDIR` environment variable -- see Setting environment variables in Linux and macOS. Note that `MPLCONFIGDIR` sets the location of both the configuration directory and the cache directory.

- Debug: 

    - `plt.set_loglevel('info')` 
    - `logging.basicConfig(level="DEBUG")` through standard python `logging` module before importing `matplotlib`
