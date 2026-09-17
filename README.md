# Bash UNIX Coursework

Integer statistics and directory-size shell revision exercises.

## Contents

| Folder | Course/Lab | Topic | Language/Platform |
| --- | --- | --- | --- |
| `revision2ex2.sh` | Existing archived exercises | Validates integer arguments and prints sum, min, max, count and average. | Bash |
| `revisionEx4.sh` | Existing archived exercises | Reads directory names from stdin and finds largest du-reported directory. | Bash |
| `acsc372/Assignment` | Additional Mac/USB coursework | See detailed contents below | Bash |
| `acsc372/Finals_Revision` | Additional Mac/USB coursework | See detailed contents below | Bash |
| `acsc372/Revision-Lab-Test-2` | Additional Mac/USB coursework | See detailed contents below | Bash |
| `acsc372/lab03` | Additional Mac/USB coursework | See detailed contents below | Bash |

Each folder is an independent exercise or project. Original names, source, dependency versions and required project configuration are preserved.

## Getting Started

Use Bash with UNIX `du`/`cut` and `bc`. Run `bash revision2ex2.sh 3 5 8`. For directory sizes, pipe readable directory names into `bash revisionEx4.sh`.

## Validation

Lightweight local checks: Bash syntax. Compilation and syntax checks do not verify application behavior. Source is preserved; interactive application behavior was not executed during archival.

## Notes

Original implementation is preserved. Build outputs, dependencies, machine-specific IDE state, backups, submission documents and private runtime data are excluded. No license has been inferred for the original work.

## Additional ACSC372 exercises

Frederick University shell labs and revision scripts retained as independent exercises.

| Folder | Course/Lab | Topic | Language/Platform |
| --- | --- | --- | --- |
| `acsc372/lab03` | ACSC372 / Lab 3 | Integer sum/product and file-type classification | Bash / UNIX |
| `acsc372/Assignment` | ACSC372 / Assignment | Interactive substring/length menu | Bash |
| `acsc372/Finals_Revision` | ACSC372 / Final revision | Minimum arguments, display file lines, descending unique numbers | Bash / sort / uniq |
| `acsc372/Revision-Lab-Test-2` | ACSC372 / Revision | Celsius/Fahrenheit conversion | Bash / bc |

Run each with Bash, for example `bash acsc372/lab03/lab3ex2.sh` or `bash acsc372/Finals_Revision/Final2024Q2B.sh 7 2 9`. The file-type and line-display scripts take a path argument. The string and temperature scripts show interactive menus; temperature conversion requires `bc`. Provide valid numeric inputs to the numeric exercises. Final2025Q2B truncates/writes `numbers.txt` in the working directory; run it from a disposable directory to retain the bundled sample.

Mac validation: all seven added scripts passed `bash -n`; interactive behavior remains unverified. Exercises with clear source bugs were withheld for a separate repair phase.
