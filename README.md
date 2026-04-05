# cls-unpackmp2

**cls-unpackmp2** is a preprocessing filter for **FreeArc**.  
It detects and decompresses **MP2 streams** to improve further compression efficiency.

---

## Parameters

| Parameter | Description |
|------------|------------|
| `fpb=[N]` | Frames per block (`4096–65535`, default: `4096`) |

---

## Example

```cmd
arc.exe a -ep1 -dses --dirs -s; -lc- -di -i2 -r -m=unpackmp2:fpb=8192 data.arc packeddata\*
```

---

## Support the Project

[![Support on Patreon](https://c5.patreon.com/external/logo/become_a_patron_button.png)](https://www.patreon.com/Shegorat)

If you find this project useful, consider supporting development on Patreon.
