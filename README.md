# YRpp4ida

A single C header file (`yrpp4ida.h`) for parsing `gamemd.exe` of
**Command & Conquer: Yuri's Revenge** in IDA Pro.

## Usage

1. Open your `gamemd.exe` database in IDA.
2. `File` -> `Load file` -> `Parse C header file...` (or press `Ctrl+F9`) and
   pick `yrpp4ida.h`.

Some virtual table addresses are also marked in the file, so you can search for them
directly.

## Note

This is not a complete map of the executable, but it is practical enough for everyday
work. It started from public YRpp sources and was extended and fixed during my own
reversing.

## License

MIT - see [LICENSE](LICENSE).

---

CrimRecya (绯红热茶)
