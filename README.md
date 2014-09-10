LibBase64-1.0
=============

LibBase64-1.0 is a LibStub-based library provding base64 encoding/decoding using MIME's Base64.

!(https://api.travis-ci.org/Adirelle/LibBase64-1.0.svg?branch=master)

Sample
------

```lua
local base64 = LibStub('LibBase64-1.0')

local encoded = base64:encode('somestring')

local decoded = base64:decode(encoded)
```

License
-------

LibBase64-1.0 is licensed with the GNU Public License version 3.0.
