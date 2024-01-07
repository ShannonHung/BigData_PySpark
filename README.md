# Data/Use Case
* Why is your problem a "big data problem"?
* Why can’t you solve it traditional storage/analytics/database technologies?
* Where does your prototype take shortcuts, what would have to be considered in real scenarios?
# Scaling
* What happens when the amount of data increases in the orders of magnitude (1x/10x/100x... or 
2x/4x/8x/16x/...)? 
* What happens if request or query intake increases ore latency conditions decrease in magnitude? 
* How does the "data" run through the system? Which paths are IO-bound/Memory-bound/CPUbound? 
* Which paths are easy/more difficult to scale? How is scaling, how are data/requests/queries partitioned? What happens when data or queries skew and bias
# Real-time capable and costs
* Is your system real-time capable? Are there any setup/bootstrapping etc. costs?
# Hardware and software resources
* How would you dimension a real system or setup given realistic data or query sets?
# Fault Tolerance
* How does the system behave under Node/CPU/Memory/Hardware/... errors and failures?
* What happens during network interruptions and partitioning?
* How do error handling mechanisms affect efficiency/scale/latency/throughput/... etc.? Are there any 
worst/best case considerations?
# Implementation
* Which system/software/Spark/HDFS components contribute to the execution and how?
* How and with which components (executors, workers, HDFS-nodes/storage-nodes), etc., are the data 
analyses/queries/queries mapped to the hardware resources (CPU/memory/disk/network)
