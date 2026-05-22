 # Linux Backup Automation Project

This project automates Linux directory backups using Bash scripting and uploads compressed backup files to AWS S3.

## Technologies Used

- Linux (CentOS Stream)
- Bash Scripting
- AWS CLI
- Amazon S3
- Cron Jobs

## Features

- Automated backup creation
- Timestamped backup files
- Compression using tar.gz
- Automatic upload to AWS S3
- Cron job scheduling

## Project Workflow

1. Select folder to back up
2. Compress files using tar
3. Store backup locally
4. Upload backup to AWS S3
5. Automate process using cron

## Commands Used

### Run Script

```bash
./BackupScript
