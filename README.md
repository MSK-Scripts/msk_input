# msk_input
[STANDALONE] Input Windows

## Description
* Opens an Input Window

![msk_input_small](https://github.com/MSK-Scripts/msk_input/assets/49867381/b579f3a1-fe47-4134-b0f6-002f06d3f7fe)
![msk_input_big](https://github.com/MSK-Scripts/msk_input/assets/49867381/7c74e5fb-3abd-4c12-9f9e-0c11154d3266)

## Usage

**Small Input Window**
```lua
exports.msk_input:openInput('This is a Header', 'This is a Placeholder', function(input)
    if not input then return end

    print(input)
end)
```

**Big Input Window**
```lua
exports.msk_input:openInput('This is a Header', 'This is a Placeholder', true, function(input)
    if not input then return end

    print(input)
end)
```

## Credits
* [Code Service](https://discord.com/invite/Z4Xv5zBQms)
