# High Memory Usage

## Problem

Server performance is slow due to high memory utilization.

## Investigation Steps

### Check Memory Usage

```bash
free -m
```

### View Processes

```bash
top
```

### Sort by Memory

```bash
ps aux --sort=-%mem
```

## Resolution

- Identify memory-consuming process
- Review application logs
- Restart application if approved
- Coordinate with application team

## Interview Answer

If memory usage becomes high, I will identify the process consuming memory, investigate logs, coordinate with relevant teams, and take corrective action according to procedures.
