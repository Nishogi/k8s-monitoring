# V2

Compared to V1, this version added the possibility to drill/down to the JVM.

Composed of two dashboards.

---



# First dashboard : 

     Cluster overview

## Metrics by row

- General
    - Disclaimer
    - Number of nodes
    - Number of pods
    - Number of pods by namespace
    - Pods restarts by namespace over time
    - Pods not ready by namespace over time
    - Number of pods with no CPU limit by namespace
    - Number of pods with no memory limit by namespace

- CPU :
    - Number of CPU cores
    - Usage
    - Usage by pod

- Disk :
    - Total filesystem size
    - Usage
    - Disk I/O

- Memory :
    - Total memory size
    - Usage
    - Usage by pod

- Network :
    - Packets
        - receive-drop
        - receive-errors
        - receive-packets
        - transmit-drop
        - transmit-errors
        - transmit-packets

---

# Second dashboard : 

    JVM focused view

## Variables

Default time zone is last 3 hours.

Possibility to select the namespaces, pods that you want to monitor.

Default are z-gcworkers-nfs-2023-1-1 for namespace and geoservices-euro-5db44845c4-zbt4x for pod.


## Metrics by row

- General
    - Pod name
    - Status
    - Start time
    - UP time

- CPU :
    - Total CPU load
    - System CPU load
    - User CPU load
    - CPU load over time


- Memory :
    - Available physical memory
    - Used physical memory
    - Used physical memory over time
    - Heap memory usage over time
    - Non heap memory usage over time
    - Memory pool usage over time
    - Detail of each pool over time

- Threads :
    - Threads state (blocked, new, runnable, terminated, timed_waiting, waiting)

- Tomcat :
    - Request count over time
    - Processing time over time
    - Thread pool over time
    - Server request errors over time
    - Collection count