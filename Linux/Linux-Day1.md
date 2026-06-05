# Linux Learning Log

## Linux Fundamentals Part 1

### Commands Learned

#### pwd
- Shows the current working directory.
- Like WhatsApp live location in Linux.

#### ls
- Lists files and folders in the current directory.

#### cd
- Used to move into another folder.

Example:
```bash
cd folder4
```

#### cat
- Displays the contents of a file.
- Shows everything inside the file.

Example:
```bash
cat note.txt
```

#### find
- Used to locate files.

Example:
```bash
find -name passwords.txt
```

- `-name` means search by file name.
- Linux replies with the location of that file.

#### grep
- Searches for specific text inside a file.
- Like searching your roll number in a PDF.

Example:
```bash
grep THM access.log
```

- Shows only lines containing THM.

---

### Operators Learned

#### &
- Runs a command in the background.

Example:
```bash
download_movie &
```

- Download continues while you do other work.

#### &&
- Run the second command only if the first succeeds.

Example:
```bash
command1 && command2
```

#### >
- Replaces old content with new content.

Example:
```bash
echo hello > greetings
```

#### >>
- Adds content without deleting old content.

Example:
```bash
echo hola >> greetings
```

Output:
hello
hola

---

### TryHackMe Room Completed

- Linux Fundamentals Part 1

### Key Understanding

cat = Show everything

grep = Search something specific

find = Find where a file is located

pwd = Show current location

> = Replace content

>> = Add content