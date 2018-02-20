# Rutcher

A simple program which searches for a pattern in a binary file and patches it with a new one!

## Usage

```bash
rutcher -s 12345678 -r 90909090 ~/patchme.exe /tmp/patched.exe
```

This will search for the bytes `0x12 0x34 0x56 0x78` and patch every occurrence with `0x90 0x90 0x90 0x90`.

**Note**: since this tool is aimed in patching binary files, the patterns should probably have the same length.
