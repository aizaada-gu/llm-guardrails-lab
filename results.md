# Model comparison (CPU only)

| Model | Size | First load | Tokens/sec | Avg answer time |
|---|---|---|---|---|
| llama3.2:1b | 1.3 GB | 3.5s | 23.0 | 4.1s |
| gemma3:1b | 0.8 GB | 1.7s | 23.9 | 2.5s |
| qwen2.5:1.5b | 1.0 GB | 25.3s | 27.3 | 10.0s |
| llama3.2:3b | 2.0 GB | 4.7s | 13.5 | 6.1s |
| phi4-mini | 2.5 GB | 5.5s | 11.1 | 5.8s |
| gemma3:4b | 3.4 GB | 10.0s | 10.9 | 8.1s |

Accuracy: read the answers below and grade each one.

## Answers

### llama3.2:1b
**Q:** How do I list hidden files in Linux? Answer in 2 sentences.
**Correct:** ls -a (current folder only)

To list hidden files in Linux, you can use the `ls` command with the `-a` option, which stands for "all", and the `--hidden` option, which lists only files that are not visible by default. This will display a list of files that are typically hidden, such as those starting with a dot (`.`) or a tilde (`~`), and are not listed by default.

### llama3.2:1b
**Q:** What does chmod 755 do to a file? Answer in 2 sentences.
**Correct:** owner rwx, group and others r-x

chmod 755 changes the permissions of a file to allow the owner to read, write, and execute the file, while the group and others have read and execute permissions. This means that only the owner can modify the file, while the group and others can only read the file, and the file can be executed by anyone.

### llama3.2:1b
**Q:** What port does SSH use by default? Answer in 1 sentence.
**Correct:** 22

SSH (Secure Shell) uses port 22 by default for secure connections.

### gemma3:1b
**Q:** How do I list hidden files in Linux? Answer in 2 sentences.
**Correct:** ls -a (current folder only)

You can use the `ls -la` command to list all files and directories, including hidden files, which start with a dot (`.`).  This will show you all files, even those that are normally hidden.

### gemma3:1b
**Q:** What does chmod 755 do to a file? Answer in 2 sentences.
**Correct:** owner rwx, group and others r-x

`chmod 755` sets the permissions on a file to allow the owner to read, write, and execute, and the group and others to read and execute it. This permission setting is generally considered secure for most files.

### gemma3:1b
**Q:** What port does SSH use by default? Answer in 1 sentence.
**Correct:** 22

SSH typically uses port 22 by default.

### qwen2.5:1.5b
**Q:** How do I list hidden files in Linux? Answer in 2 sentences.
**Correct:** ls -a (current folder only)

In Linux, you can list hidden files by using the `ls` command with the `-a` option, which stands for "all," including hidden files.

### qwen2.5:1.5b
**Q:** What does chmod 755 do to a file? Answer in 2 sentences.
**Correct:** owner rwx, group and others r-x

The command `chmod 755` changes the permissions of a file to allow read, write, and execute permissions for the owner, and read and execute permissions for the group and others.

### qwen2.5:1.5b
**Q:** What port does SSH use by default? Answer in 1 sentence.
**Correct:** 22

SSH uses port 22 by default.

### llama3.2:3b
**Q:** How do I list hidden files in Linux? Answer in 2 sentences.
**Correct:** ls -a (current folder only)

To list hidden files in Linux, you can use the `ls -a` command, which displays all files and directories, including hidden ones. Alternatively, you can use the `ls -A` command, which is similar to `ls -a` but also displays the current working directory, making it easier to navigate.

### llama3.2:3b
**Q:** What does chmod 755 do to a file? Answer in 2 sentences.
**Correct:** owner rwx, group and others r-x

chmod 755 sets the permissions of a file to allow the owner to read, write, and execute, while also allowing group members to read and execute, and allowing others to read and execute. This means that the owner has full control, group members have limited access, and others have no access to the file's contents.

### llama3.2:3b
**Q:** What port does SSH use by default? Answer in 1 sentence.
**Correct:** 22

SSH typically uses port 22 by default.

### phi4-mini
**Q:** How do I list hidden files in Linux? Answer in 2 sentences.
**Correct:** ls -a (current folder only)

To list hidden files in Linux, use the command `ls -la` in the terminal. Hidden files typically start with a dot (.) and are not displayed by default.

### phi4-mini
**Q:** What does chmod 755 do to a file? Answer in 2 sentences.
**Correct:** owner rwx, group and others r-x

chmod 755 sets the file's permissions so that the owner has read, write, and execute permissions (7), while the group and others have read and execute permissions (5 and 5). This allows the owner to modify the file, while others can only read and execute it.

### phi4-mini
**Q:** What port does SSH use by default? Answer in 1 sentence.
**Correct:** 22

SSH uses port 22 by default.

### gemma3:4b
**Q:** How do I list hidden files in Linux? Answer in 2 sentences.
**Correct:** ls -a (current folder only)

To list hidden files in Linux, use the `ls -a` command, which displays all files, including those starting with a dot (.). Alternatively, you can use `ls -la` to list files in long format, also showing hidden files.

### gemma3:4b
**Q:** What does chmod 755 do to a file? Answer in 2 sentences.
**Correct:** owner rwx, group and others r-x

`chmod 755` sets the file permissions to allow the owner to read, write, and execute, while granting the group and others read and execute permissions. This is a common permission setting for executable scripts and directories, promoting security and usability.

### gemma3:4b
**Q:** What port does SSH use by default? Answer in 1 sentence.
**Correct:** 22

SSH typically uses port 22 by default.
