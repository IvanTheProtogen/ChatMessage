In order to acquire it, slap this block of code onto your script:

```lua
loadstring(game:HttpGet("https://github.com/IvanTheProtogen/ChatMessage/raw/main/main.lua")()("Hello World!");
```

If you wanna use it multiple times, you can use `local`:

```lua
local chatmsg = loadstring(game:HttpGet("https://github.com/IvanTheProtogen/ChatMessage/raw/main/main.lua")()

chatmsg("Hello World!")
```
