# High CPU Usage

## Problem

Application response time is slow.

## Investigation Steps

### Check CPU Usage

```bash
top
```

### View Processes

```bash
ps aux --sort=-%cpu
```

### Monitor System

```bash
vmstat 5
```

## Resolution

- Identify high CPU consuming process
- Restart application if approved
- Coordinate with application team
- Monitor after resolution

## Interview Answer

If CPU usage becomes high, I will use top and ps commands to identify the process consuming resources, investigate logs, coordinate with the application team if needed, and ensure the system returns to normal.
