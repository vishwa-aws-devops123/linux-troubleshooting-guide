# SSH Connection Issue

## Problem

Unable to connect to the Linux server using SSH.

## Investigation Steps

### Check Network Connectivity

```bash
ping server-ip
```

### Check SSH Service

```bash
systemctl status sshd
```

### Verify SSH Port

```bash
ss -tulnp | grep 22
```

### Check Firewall Rules

```bash
firewall-cmd --list-all
```

### Review SSH Logs

```bash
tail -f /var/log/secure
```

## Resolution

- Start SSH service if stopped
- Verify firewall rules
- Verify user permissions
- Verify network connectivity

## Interview Answer

If SSH access is not working, I will first verify network connectivity, check whether the SSH service is running, review firewall settings, examine SSH logs, and restore access based on the findings.
