# Linux Command Line Practice

## Users Management
- create a new Linux user account and change its password
  ```
  useradd [option] *username*
  passwd *username*
  ```
  
- Delete a user
  ```
  userdel *username*
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
  mkdir *directory*
  ```

- Change directory.
  ```
  cd *directory*
  ```

- Create an empty file.
  ```
  touch *file*
  ```

- Copy files or directories.
  ```
  cp *file* *copied file path/file*
  ```

- Move or rename files or directories.
  ```
  mv *file* *new path/file*
  ```

- Display a line of text/string that is passed as an argument.
  ```
  echo "Hello, World!" > index.html
  ```

- Lists, combines, and writes file content to the standard output (Concatenate file).
  ```
  cat index.html
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

- Query Internet name servers for DNS lookups.
  ```
  nslookup google.com
  ```

## File Permissions and Editing

- Change the file modes or Access Control Lists.
  ```
  chmod g+w index.html
  ```

## File Compression and Archives

- Compresses/Decompresses items into/from **ZIP** file
  ```
  zip [option] *zipfile* *file1* *file2*
  unzip [option] *zipfile*
  ```

- Compresses/Decompresses items into/from **TAR** file
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
- Compares two files' content and outputs the difference
  ```
  diff [option] file1 file2
  ```
- Writes the user's input to Terminal's output and files
  ```
  *command* | tee [option] file1
  ```
## File Management
- Finds a file in the database system
  ```
  locate -i 
  ```
- Searches for files within a specific directory
  ```
  find [option] [path] [
  ```
## Disk Usage

- Estimate file space usage.
  ```
  du -sh project
  ```




