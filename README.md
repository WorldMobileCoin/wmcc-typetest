# wmcc-typetest (WorldMobileCoin)

__NOTE__: The first release of wmcc-typetest.

---

## WMCC TypeTest

Utility for WMCC.

### Usage:
```js
const assert = require('assert');
const TypeTest = require('wmcc-typetest');

assert(TypeTest.isAscii('teststring'));
assert(TypeTest.isUint(7));
assert(TypeTest.isHex('FFFF00'));
assert(TypeTest.isHex('FFFF00S')); // fail
```

**WorldMobileCoin** is a new generation of cryptocurrency.

## Disclaimer

WorldMobileCoin does not guarantee you against theft or lost funds due to bugs, mishaps,
or your own incompetence. You and you alone are responsible for securing your money.

## Contribution and License Agreement

If you contribute code to this project, you are implicitly allowing your code
to be distributed under the MIT license. You are also implicitly verifying that
all code is your original work.

## License

--Copyright (c) 2018, Park Alter (pseudonym)  
--Distributed under the MIT software license, see the accompanying  
--file COPYING or http://www.opensource.org/licenses/mit-license.php