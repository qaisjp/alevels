Proving that if a < b, then a % b == a
---
```lua
local cycles = 10000
for i = 0, cycles-1 do
    if (i % cycles) ~= i then
        print("Error: ", i, i % cycles)
        return
    end
end
print("Success!")
```
