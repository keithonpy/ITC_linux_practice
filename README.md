# Linux Command Line Practice

## Users Management
- create a new Linux user account and change its password
  ```
  useradd [option] *username*
  ```
  ```
  passwd *username*
  ```
## File and Directory Management

- Print the current working directory.
  ```
  pwd
  ```

- List files and directories.
  ```
  ls
  ```

- Create a new directory.
  ```
  mkdir project
  ```

- Change directory.
  ```
  cd project
  ```

- Create an empty file.
  ```
  touch index.html
  ```

- Copy files or directories.
  ```
  cp index.html index_backup.html
  ```

- Move or rename files or directories.
  ```
  mv index_backup.html backup/
  ```

- Display a line of text/string that is passed as an argument.
  ```
  echo "Hello, World!" > index.html
  ```

- Concatenate files and print on the standard output.
  ```
  cat index.html
  ```

- Print newline, word, and byte counts for each file.
  ```
  wc -l index.html
  ```

## System Information and Management

- Report a snapshot of the current processes.
  ```
  ps
  ```

- Send a signal to a process, usually related to stopping the process.
  ```
  kill 1234
  ```

- Display or set the system date and time.
  ```
  date
  ```

 - Show the command-line history.
  ```
  history
  ```

## Networking

- Configure or display network interface parameters.
  ```
  ifconfig
  ```
  
- Check the network connection to a server.
  ```
  ping -c 4 google.com
  ```

- Query Internet name servers for DNS lookups.
  ```
  nslookup google.com
  ```

## File Permissions and Editing

- Change the file modes or Access Control Lists.
  ```
  chmod g+w index.html
  ```

- Stream editor for filtering and transforming text.
  ```
  sed -i 's/World/Bash/g' index.html
  ```

## File Compression and Archives

- An archiving utility.
  ```
  tar -czvf backup.tar.gz backup/
  tar -xzvf backup.tar.gz
  ```

## Downloading and Web Requests

- Transfer data from or to a server.
  ```
  curl http://example.com -o page.html
  ```

- Non-interactive network downloader.
  ```
  wget http://example.com/file
  ```

## Text Processing

- Search for patterns in files.
  ```
  grep "World" index.html
  ```

- Sort lines of text files.
  ```
  sort page.html
  ```

- Output the first part of files.
  ```
  head -n 10 page.html
  ```

- Output the last part of files.
  ```
  tail -n 10 page.html
  ```

## Disk Usage

- Estimate file space usage.
  ```
  du -sh project
  ```

## Environment and Variables

- Set an environment variable.
  ```
  export MY_VAR=test
  ```

This cheat sheet covers the basics of Linux commands for file management, system information, networking, file permissions, text processing, and more.
