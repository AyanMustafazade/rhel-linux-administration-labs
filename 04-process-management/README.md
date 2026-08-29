# Linux Process Management

Hands-on Red Hat Enterprise Linux (RHEL) labs focused on monitoring, controlling, and managing Linux processes from the command line.

## Skills Practiced

- Process monitoring
- PID identification
- Foreground and background processes
- Process termination
- Process priority management
- Real-time process monitoring
- Filtering processes
- Parent and child process analysis

## Practical Tasks

### Process Creation & PID Identification

Created test processes and identified their Process IDs (PIDs).

```bash
sleep 300
ps aux
ps -ef
```

### Process Termination

Identified running processes and terminated them using process management commands.

```bash
kill <PID>
kill -9 <PID>
```

### Background Processes

Started processes in the background and monitored their status.

```bash
sleep 500 &
jobs
```

### Real-Time Process Monitoring

Used `top` to monitor running processes and system resource usage.

```bash
top
```

### Process Priority

Practiced starting processes with custom priorities and modifying the priority of existing processes.

```bash
nice -n 10 <command>
renice <priority> -p <PID>
```

## Lab Documentation

The attached lab document contains practical process management exercises, terminal commands, verification results, and screenshots.

## Key Takeaways

This lab provided hands-on experience with Linux process monitoring and control, including PID management, background processes, process termination, real-time monitoring, and process priority management.
