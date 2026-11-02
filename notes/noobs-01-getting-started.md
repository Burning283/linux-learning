\# Linux for Noobs – Lab 1: Getting Started with Linux

\*\*Date:\*\* 2 Nov 2026

\*\*Source:\*\* LabEx – Linux for Noobs



\## Key idea

The terminal works in a loop: \*\*type a command → press Enter → read the result.\*\*



\## Commands I learned



| Command | What it does | Example |

|---|---|---|

| `pwd` | Shows which folder I'm in | `pwd` → `/home/labex` |

| `echo` | Prints text to the screen | `echo "Hello Linux"` |

| `date` | Shows the current date and time | `date` |

| `cal` | Shows a calendar | `cal`, `cal 2026` |

| `expr` | Does simple maths | `expr 5 + 3` → `8` |

| `figlet` | Prints big ASCII-art text | `figlet Hello` |

| `clear` | Clears the screen | `clear` (or `Ctrl + L`) |



\## Options

Options change how a command behaves. Example:

```bash

date +"%Y-%m-%d"   # prints only the date, e.g. 2026-11-02

```



\## Saving output to a file

```bash

date > today.txt          # > creates/overwrites the file

echo "Day 1" >> log.txt   # >> adds to the end of the file

cat today.txt             # show what's in the file

```



\## Gotchas

\- `expr` needs spaces: `expr 5 + 3` works, `expr 5+3` doesn't.

\- To multiply, write `expr 4 \\\* 2` (the `\*` needs a backslash).

\- `>` overwrites a file with no warning. Use `>>` to add to it instead.



