# Magisk Enable Mifare Classic

## How

Ideally, you should replace `system/vendor/etc/libnfc-nci.conf` with the equivalent of this file on your phone. Then, just append the last two lines, which enable the Mifare Classic Reader.

```
# Enable Mifare Classic NFC Smartcards.
LEGACY_MIFARE_READER=1
```

## License

Copyright © 2022  Akito <the@akito.ooo>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.