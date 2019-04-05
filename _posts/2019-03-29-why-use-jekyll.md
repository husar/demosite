---
title: Ukážka 2
date: 2019-03-29 11:13
lead: "Čo chceš?"
category: coje
subtitle: Naše ukážky
---

---
Some text with an inline `code` snippet
 .my-link {
        text-decoration: underline;
    }
    **The quick brown [fox][1], jumped over the lazy [dog][2].**

[1]: https://en.wikipedia.org/wiki/Fox "Wikipedia: Fox"
[2]: https://en.wikipedia.org/wiki/Dog "Wikipedia: Dog"
[Dog](https://en.wikipedia.org/wiki/Dog "Wikipedia: Dog")
\*literally\*
<button class="button-save large">Big Fat Button</button>
\~\~deleted words\~\~
==oooh fancy==
https://ghost.org
The quick brown fox[^1] jumped over the lazy dog[^2].

[^1]: Foxes are red
[^2]: Dogs are usually not red
```language-javascript
   [...]
```
// # Notifications API
// RESTful API for creating notifications
var Promise            = require('bluebird'),
    _                  = require('lodash'),
    canThis            = require('../permissions').canThis,
    errors             = require('../errors'),
    utils              = require('./utils'),

    // Holds the persistent notifications
    notificationsStore = [],
    // Holds the last used id
    notificationCounter = 0,
    notifications;
    