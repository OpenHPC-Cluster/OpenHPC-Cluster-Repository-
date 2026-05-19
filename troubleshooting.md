# Troubleshooting
## this is a document detailing the issues faced by the team during the creation of the cluster.

### Issue 001:
Plan to use RHEL pivoted to Alma Linux due to the fact that RHEL (from Free dev subscription) has a limit of 10 images, and we are using ~10-12 nodes, to be on the safe side and not hit a paywall, we chose to move to a enterprise grade yet completely free Linux distribution which is Alma Linux -[Samuel Durai] 

### Issue 002
Expected CPU : i5-7400U 
CPU's Received : i5-4460 & i5-4460U
this measurably reduces the expected calculations of the performance of this project: pivoting from a High performance cluster, to a learning cluster to prove our in-depth knowledge of bare metal on legacy systems. -[Samuel Durai]
