# msk_input
[STANDALONE] Input Windows

## Description
* Opens an Input Window

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
* [Code Services](https://discord.com/invite/Z4Xv5zBQms)