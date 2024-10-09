# CHANGELOG


## v0.3.2 (2024-10-09)

### Fixes

* fix: Bump plum-econet lib version to 0.11.0 ([`a926c5a`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/a926c5ac49444951d3daced03f42a45176525323))


## v0.3.1 (2024-09-30)

### Fixes

* fix: Do proper validation of URL ([`4211358`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/4211358c425500aa3b201a9fd5f8294337d475c1))


## v0.3.0 (2024-09-29)

### Code Style

* style: Fix python code style ([`de4799f`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/de4799f6e2a450ecb08ee786469ec4a8c39115b2))

### Continuous Integration

* ci: Don't run tests again on default branch ([`0bae9e1`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/0bae9e133a8c62f73cd910659c2c0708215c5403))

### Features

* feat: Add summer_mode switch ([`4b9ef0f`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/4b9ef0f9512f9e56d3e0b54d2ce39534b161802a))

* feat: Validate URL input ([`e191169`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/e19116948dcb71fd36f1136f5ca775c11fe5b878))

* feat: Include prefix in sensors ([`fb6fa50`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/fb6fa50347364afff55854e8ad8055f3c956e727))

* feat: Add prefix name to WaterHeaters ([`4664339`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/4664339145d342c7c2548af8a26dd52846c120c6))

### Fixes

* fix: Update plum-econet dependency version ([`0efa41a`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/0efa41a0a3725ee42b687d6cbe452ede4eeea12f))


## v0.2.3 (2024-09-25)

### Fixes

* fix: Bump plum-econet lib one more time ([`db34e2c`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/db34e2ca2c234220afbd92a0f9c1d0beb30f4d84))


## v0.2.2 (2024-09-25)

### Fixes

* fix: Update upstream plum-econet library version ([`64c52df`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/64c52df0d5bab2d2bba12bda0ec89157cc877c09))


## v0.2.1 (2024-05-20)

### Code Style

* style: Reformatted code for black ([`cdd2d66`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/cdd2d66a5b42df543bf188765ef974d19dd9862d))

### Fixes

* fix: Try/Catch TypeError and try to convert to float

Added extra logging ([`5a3b9e4`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/5a3b9e4b5243f126c828deca21dac6d4c1a2577f))

### Unknown

* Merge branch 'feature/Fix_crash_on_wrong_value_type' into 'main'

Fix conversion error that occures randomly for some sensors

See merge request bulgur/plum-econet-ha!2 ([`9e9abd9`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/9e9abd99c9bd0bc71848710604b029fa5497a828))


## v0.2.0 (2024-02-28)

### Code Style

* style: Fix style to please black linter ([`4c49a51`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/4c49a510bf5a3ed1bad665c4f36b181692971f72))

### Features

* feat: Set device class for binary sensors ([`3205194`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/3205194b4060f7cc3952dbeb26e5cff676f854a6))

* feat: Move BinarySensors to it's own platform to initialize corectly ([`b298f3d`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/b298f3d96e4c89a3363bac653c72582b2d108972))

### Fixes

* fix: Remove debug print ([`6dd78e1`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/6dd78e15ca01e91cf5c8d35a8928b193f10d317b))

* fix: Change boiler icon depending on state ([`22a39c2`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/22a39c2d1cd52b4e0e6272942a2e63d375260acf))

* fix: bump plum-econet lib version ([`e9870cd`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/e9870cdad62770d3b44681c85fb933f4a65c4a2f))

### Unknown

* Merge branch 'feature/improvements' into 'main'

Improvements

See merge request bulgur/plum-econet-ha!1 ([`4a2f74b`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/4a2f74b142d20e77e433d8f7ea10f8d277ec4f90))


## v0.1.7 (2024-02-16)

### Fixes

* fix: Update hacs.json with correct filename ([`ef0fd30`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/ef0fd305000079dba494b3800d643bb9418c5059))


## v0.1.6 (2024-02-16)

### Fixes

* fix: Update filename in hacs.json instead of manifest.json ([`fb46950`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/fb46950f33a2cea07d476b9bfdb624aa06750457))


## v0.1.5 (2024-02-16)

### Fixes

* fix: Update filename, fix release version ([`6e0cffd`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/6e0cffd69422c913a8c4c89182d12c7259d44778))


## v0.1.4 (2024-02-16)

### Fixes

* fix: Add manifest.json to root dir as well ([`5c986b1`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/5c986b1e8829c8ab1b4e6b834cbede4e5e1cb54a))


## v0.1.3 (2024-02-16)

### Continuous Integration

* ci: Exit if no version change ([`ddce1d4`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/ddce1d4e635b45d04bc05c5e5abe7b93d8feb1e3))

### Fixes

* fix: Add content_in_root setting ([`d23f77c`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/d23f77c1a73f1c10fa0ba08f01a1c526de26f6a7))


## v0.1.2 (2024-02-16)

### Continuous Integration

* ci: Don't edit comment ([`b868e0e`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/b868e0e14d5c78a191effef5ffd802208342ed88))

### Fixes

* fix: Install openssh-client ([`002f783`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/002f783a88e1eddc2295618c2270a875d3948e63))


## v0.1.1 (2024-02-16)

### Fixes

* fix: Aparently Variable name matters for github cli ([`e875699`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/e875699cb95066aae872a196030af7a0176322d1))


## v0.1.0 (2024-02-16)

### Features

* feat: Update ci, bump version ([`90aa689`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/90aa689f61161f258b65aec605f0562775df9545))


## v0.0.1 (2024-02-16)

### Chores

* chore: Don't use zip release for now ([`e9a3b99`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/e9a3b99bbb4e5ec53c459713760b8360ba9125c7))

### Code Style

* style: Add newlines to fulfil new black requirements ([`0004cfb`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/0004cfbe572b903db8e37c39c4e7f3267d2c7867))

### Continuous Integration

* ci: Configure git ([`a6c8980`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/a6c89808ff7fa3844d955028df0e6bea5d8133b1))

* ci: Add CI and release process ([`38691c6`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/38691c6c411557d967f1b35908a281a6e9c18762))

### Fixes

* fix: bump plum-econet version ([`ae38789`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/ae38789540ce9f876dede9970503efce6207dcb3))

### Unknown

* Initial commit ([`9d32e8d`](https://gitlab.com/bulgur/plum-econet-ha/-/commit/9d32e8dd41c2f8cc2746091a94beb893796e7da1))
