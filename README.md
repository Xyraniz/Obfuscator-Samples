# Obfuscator-Samples

[![Stars](https://img.shields.io/github/stars/Xyraniz/Obfuscator-Samples?style=for-the-badge&color=gold)](https://github.com/Xyraniz/Obfuscator-Samples/stargazers)
[![Lua](https://img.shields.io/badge/Lua-000080?style=for-the-badge&logo=lua&logoColor=white)](https://www.lua.org/)

A collection of Lua files run through different obfuscators, kept as raw ground truth for anyone building detection, dumping, or deobfuscation tooling around them.

## Why this exists

There's no shortage of tools that claim to detect or unpack a given obfuscator, but very few of them are built against confirmed samples of what that obfuscator actually outputs. This repo is that raw material: a script known to have come from Moonsec, Luraph, IronBrew, or any of the others listed below, with nothing else mixed in. Each folder holds obfuscated output only — no original source, no side-by-side diff. What you do with a sample is up to you: fingerprint it for a detector, feed it to a dumper you're writing, or reverse it by hand to understand how that specific obfuscator's VM is laid out.

Questions about a specific obfuscator's behavior, or a sample that turned out wrong, go in [Issues](https://github.com/Xyraniz/Obfuscator-Samples/issues).
