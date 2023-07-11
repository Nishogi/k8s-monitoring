# V1

Composed of one dashboard.

---

# First dashboard 

## Variables

Default time zone is last 3 hours.

Possibility to select the namespaces, pods and geographical zones (for geoservices) that you want to monitor.

Default are z-gcworkers-nfs-2023-1-1 for namespace, All for pod and / for geographical zone (=plaque).
## Metrics by row

- CPU :
    - Usage
    - Usage over time
    - Usage over time (zoomed in)

- Memory :
    - Usage
    - Usage over time

- Network :
    - Received bandwidth over time
    - Transmitted bandwidth over time
    - Errors received over time
    - Received packets over time
    - Transmitted packets over time
    - Packets dropped over time

- JVM : 
    - Used JVM memory over time
    - Max JVM memory over time
    - Total JVM memory over time

- Other :
    - Pod crashes for the last 7 days over time
    - Catalina busy threads over time