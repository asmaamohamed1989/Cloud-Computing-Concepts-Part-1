# Cloud-Computing-Concepts-Part-1 : 
*	https://www.coursera.org/specializations/cloud-computing

# What is the project? 
*	The project is about implementing a **Gossip Protocol**.
*	The main functionalities of the project :
	* **Introduction** : 
	Each new peer contacts a well-known peer (the introducer) to join the group. 
	* **Membership** : 
	A membership protocol satisfies completeness all the time (for joins and failures), and accuracy when there are no message delays or losses (high accuracy when there are losses or delays). 
# How do I run the Grader on my computer ?
*	There is a grader script GraderNew.sh. It tests your implementation of membership protocol in 3 scenarios and grades each of them on 3 separate metrics. The scenarios are as follows:
	* 1. Single node failure
	* 2. Multiple node failure
	* 3. Single node failure under a lossy network.
	$ chmod +x GraderNew.sh
	$ ./GraderNew.sh
# Result
*	Points achieved: 90 out of 90 [100%]
	
