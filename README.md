# LQS Performance Experimentation

### Phase1
In this phase, the log files are named as "./phase1/<pbs_number><run_number>.csv". Here, <pbs_number> refers to the number of PBS complexes present (experimentation is done with 1, 2, 3, and 5 PBS complexes). Each experiment is repeated 50 times, from <run_number> of 0 to 49. Each csv files records the number of jobs in the queue, the response time of qstat, qsub, throughput of sleep jobs, and the expansion ratio of big jobs.