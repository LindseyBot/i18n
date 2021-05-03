# Lindsey Translations

This repository contains all lindsey translation strings currently in-use. If you want to contribute, simply follow the
format from the `en_US.properties` file on your own language's i18n file.

If you are planning on doing a lot of changes, please add them all to the same pull-request!

All contributions/pull requests are welcome!

## Translation status:

This table was last updated on 2021-05-02.

| Language              | % Translated  |
| --------------------- |:-------------:|
| en_US (English US)    | 100%          |
| pt_BR (Portuguese BR) | 0%            |

## Format

Special characters like `{0}` and `{1}` represent variables, and are filled on the order specified by the number inside
the bracket. This means a string such as:

`Hello {0}, you have {2} coins and {1} items.`

Would be filled with (assuming you had 8 items and 15 coins):

`Hello User, you have 15 coins and 8 items.`

If the language you are translating to requires moving them around (like `{0} Hello` instead of `Hello {0}`), feel free
to!
