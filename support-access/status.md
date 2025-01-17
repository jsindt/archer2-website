---
layout: section
title: Service Status
summary: Information about ARCHER2 Service Status
banner: web_banners_03.jpg
---

## Current Issues

No current issues.

## Recently Resolved Issues


### 20:00, 27 Feb 2021 - 12:30, 28 Feb 2021: Login node issues

The login nodes (UAN) have lost connection to some management services. This means that
some commands will not work on the login nodes. In particular, all commands to the
Slurm scheduler (e.g. `sbatch`, `squeue`) will not work and will return an error similar
to:

```
slurm_load_partitions: Unable to contact slurm controller (connect failure)
```

A workaround was put in place on 28 Feb 2021 to resolve this issue.

At 14:00 on Monday 1st March, the now rebooted switch was restored, meaning that interactive jobs are currently unable to run once more.

Please alert the [Service desk](mailto: support@archer2.ac.uk) if you see any further issues.

## Upcoming Maintenance Sessions

No upcoming sessions scheduled

## Completed Maintenance Sessions

There have been no recent maintenance sessions. 

