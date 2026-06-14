# Service Down Issue

## Problem

Application service is unavailable.

## Investigation Steps

### Check Service Status

```bash
systemctl status service-name
```

### Review Logs

```bash
journalctl -u service-name
```

### Check Resources

```bash
top
df -h
free -m
```

## Resolution

- Restart the service if approved
- Investigate logs
- Verify dependencies
- Escalate if application-level issue exists

## Interview Answer

If a service is down, I will check the service status, review logs, verify system resources, restart the service if approved, and coordinate with the application team if further investigation is required.
