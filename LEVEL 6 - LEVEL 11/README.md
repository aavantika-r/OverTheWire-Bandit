OverTheWire Bandit – Linux Practice

Level 6 → Level 7 – Finding Files

Objective: Find a file based on its owner, group and file size.

find / -user bandit7 -group bandit6 -size 33c 

Concepts learned:

- "find" – Search files and directories.
- "-user" – Search by file owner.
- "-group" – Search by group.
- "-size" – Search by file size.
---

Level 7 → Level 8 – Searching Text

Objective: Find the password associated with the word "millionth" in "data.txt".

grep "millionth" data.txt

Concepts learned:

- "grep" – Search for matching text.
- Text searching in files.

---

Level 8 → Level 9 – Finding a Unique Line

Objective: Find the line that occurs only once in the file.

sort data.txt | uniq -u

Concepts learned:

- "sort" – Sort lines.
- "uniq" – Identify repeated lines.
- "uniq -u" – Display unique lines.
- "|" – Pipe output from one command to another.

---

Level 9 → Level 10 – Extracting Readable Strings

Objective: Find a human-readable string in binary data.

strings data.txt | grep "="

Concepts learned:

- "strings" – Extract readable text from binary files.
- "grep" – Filter matching lines.

---

Level 10 → Level 11 – Base64 Decoding

Objective: Decode Base64-encoded data.

base64 -d data.txt

Concepts learned:

- Base64 encoding.
- Base64 decoding.
- "-d" – Decode.

---

Level 11 → Level 12 – ROT13

Objective: Decode text encrypted using ROT13.

cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'

Concepts learned:

- "tr" – Translate characters.
- ROT13 – Rotate alphabetic characters by 13 positions.
- Character mapping.

---

Linux Commands Practiced

- "find"
- "grep"
- "sort"
- "uniq"
- "strings"
- "base64"
- "tr"
- "cat"
- "file"
- "xxd"

Progress

- [x] Bandit Level 6 → 7
- [x] Bandit Level 7 → 8
- [x] Bandit Level 8 → 9
- [x] Bandit Level 9 → 10
- [x] Bandit Level 10 → 11
- [x] Bandit Level 11 → 12

Platform: OverTheWire Bandit
Focus: Linux command-line skills and basic security concepts
