# gopnik

Generic Over-Provisioning Nuker and Inspection Kit

> aka Private Cloud Resource Squatting Detector

1. Agent in instances that will watch
  - RAM used/free
  - RAM access frequency and whether it can be swapped
  - Network traffic
  - CPU use
  - Disk use

2. Job that will look for abandoned cinder volumes
