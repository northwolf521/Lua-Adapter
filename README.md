# Lua-Adapter
Use this lightweight wrapper- / adapter-class as an interface between Lua and C++.

Usage:

      LuaAdapter lua{"test.lua"};
      int width {0};
      lua.Get("width", width);  // width=600
» see [examples](https://github.com/JlnWntr/Lua-Adapter/blob/master/examples) for more examples

Requirements:

- [Download and install Lua](https://www.lua.org/download.html).
- g++-8 or higher

If `apt-get install g++-8` does not work on your Debian, try 

    add-apt-repository ppa:ubuntu-toolchain-r/test && sudo apt-get update 
first.
