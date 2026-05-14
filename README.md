# linux-notes

## File & Directory Commands

### pwd
Shows the current directory.

```bash
pwd
```

---

### ls
Lists files and directories.

```bash
ls
ls -l
ls -a
```

---

### cd
Changes the current directory.

```bash
cd /home
cd ..
```

---

### mkdir
Creates a new directory.

```bash
mkdir test
```

---

## File Management

### cp
Copies files or directories.

```bash
cp file1.txt file2.txt
cp -r folder1 folder2
```

---

### mv
Moves or renames files.

```bash
mv old.txt new.txt
```

---

### rm
Deletes files or directories.

```bash
rm file.txt
rm -r folder
```
---
## User Management

### whoami
Displays the current logged-in user.

```bash
whoami
```

---

### useradd
Creates a new user.

```bash
sudo useradd ibrahim
```

---

### passwd
Sets or changes a user password.

```bash
sudo passwd ibrahim
```

---

### sudo
Runs commands with administrative privileges.

```bash
sudo apt update
```

---

## Permissions

### chmod
Changes file permissions.

```bash
chmod +x script.sh
chmod 755 file.sh
```

---

### chown
Changes file ownership.

```bash
sudo chown user:user file.txt
```

---

## Process Management

### ps
Displays running processes.

```bash
ps aux
```

---

### top
Shows real-time running processes.

```bash
top
```

---

### kill
Terminates a process using PID.

```bash
kill 1234
```

---

### pkill
Kills processes using process name.

```bash
pkill nginx
```

---

## Networking Commands

### ping
Checks network connectivity.

```bash
ping google.com
```

---

### curl
Transfers data from servers.

```bash
curl https://google.com
```

---

### wget
Downloads files from the internet.

```bash
wget https://example.com/file.zip
```

---

### ss
Displays socket and network information.

```bash
ss -tuln
```

---

## Package Management

### apt update
Updates package lists.

```bash
sudo apt update
```

---

### apt install
Installs packages.

```bash
sudo apt install nginx
```

---

## Disk & Storage

### df
Shows disk space usage.

```bash
df -h
```

---

### du
Shows directory/file size.

```bash
du -sh folder/
```

---

## Search Commands

### grep
Searches for text patterns.

```bash
grep "hello" file.txt
```

---

### find
Searches for files and directories.

```bash
find /home -name test.txt
```

---

## Archive & Compression

### tar
Archives files and directories.

```bash
tar -cvf archive.tar folder/
```

---

### unzip
Extracts zip files.

```bash
unzip file.zip
```
