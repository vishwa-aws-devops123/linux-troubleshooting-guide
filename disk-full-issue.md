# Disk Full Issue

## Problem

Users report that the application is slow and unable to write files.

## Investigation Steps

### Check Disk Usage

```bash
df -h
```

### Identify Large Directories

```bash
du -sh /*
```

### Find Large Files

```bash
find / -type f -size +100M
```

### Check Log Files

```bash
du -sh /var/log/*
```

## Resolution

- Remove unnecessary files if approved
- Archive old logs
- Clean temporary files
- Request additional storage if required

## Interview Answer

If a Linux server disk becomes full, I will first check disk usage using df -h, identify large files and directories using du and find commands, review logs, remove unnecessary files if approved, and escalate for storage expansion if required.
