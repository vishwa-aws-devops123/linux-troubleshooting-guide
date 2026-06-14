# Application Not Accessible

## Problem

Users report that the application is not accessible.

## Investigation Steps

### Check Server Availability

```bash
ping server-ip
```

### Check Application Service

```bash
systemctl status service-name
```

### Check Listening Ports

```bash
ss -tulnp
```

### Review Logs

```bash
tail -f application.log
```

### Check Resources

```bash
top
df -h
free -m
```

## Resolution

- Verify server availability
- Verify service status
- Review logs for errors
- Escalate to application team if required

## Interview Answer

If an application is not accessible, I will verify server availability, check service status, review logs, verify network connectivity, and coordinate with the application team if necessary.
