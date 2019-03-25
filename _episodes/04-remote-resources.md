---
title: "Using Remote Computing Resources"
teaching: 30
exercises: 0
questions:
- "How do I access remote computing resources?"
- "How do I transfer files back and forth between my own computer and the remote computing resource?"
- "How do I submit jobs on a remote computing resource?"
objectives:
- "Use ssh to connect to remote computing resources."
- "Use scp or an scp client to transfer files between computers."
- "Submit and monitor jobs on remote computing resources that use different job managers."
keypoints:
- "The ssh protocol is used to access remote computing resources."
- "The scp protocol is used to transfer files between computers."
- "Most remote computing resources will have a job manager to manage the submission and running of calculations.  Using a job manager requires creating a submission script for your job in addition to the input file for the actual program."
---
## Connecting to other computers
You will often need to connect to other computers to run calculations or use resources.  The most common way you connect to remote computers is using something called the Secure Shell Protocol or ssh.  

- [Using ssh](https://www.ssh.com/ssh/command/) If you are just learning about ssh, reading the sections *Using the Linux client, Specifying a Different User name, and Executing Remote Commands* on this page is sufficient.  

To move or copy files between computers, you use secure copy or scp.

- [Using scp](https://haydenjames.io/linux-securely-copy-files-using-scp/) If you are just learning about scp, the section *SCP examples* on this page will cover most things you need to do.

## Running jobs on remote computing resources
You can imagine that if 100 people accessed a computer at one time and all tried to submit calculations, the computer would quickly become overwhelmed.  Consequently, most of the time a remote computing system will have a *queuing system* or *workload manager*.  This type of system has a *queue* where your job waits in line until the computing resources it needs are available.  To submit a job to a computing resource that uses a queue, you need to copy your input file to the remote computer and you also need to create some type of submission script that tells the computer how to run your calculation and what computing resources it needs.  The format of submission scripts and how they are submitted to the queue depends on what type of queue management software the computer uses.  

### [Slurm](https://slurm.schedmd.com/)
- [Overview of slurm commands](https://slurm.schedmd.com/quickstart.html)   

### [Platform Load Sharing Facility (LSF)](https://www.ibm.com/support/knowledgecenter/en/SSWRJV_10.1.0/lsf_admin_foundations/working_lsf.html)
- [Overview of LSF commands](https://www.ibm.com/support/knowledgecenter/en/SSWRJV_10.1.0/lsf_admin_foundations/run_lsf_jobs.html)  

### Portable Batch System (PBS)
- [Overview of PBS commands](https://www.nas.nasa.gov/hecc/support/kb/commonly-used-pbs-commands_174.html)

### [GridEngine](http://gridscheduler.sourceforge.net/)
- [Overview of GridEngine commands](http://gridscheduler.sourceforge.net/howto/basic_usage.html)

## Additional Resources
[This lesson](https://hpc-carpentry.github.io/hpc-intro/) from [the HPC Carpentry project](https://github.com/hpc-carpentry) may also be useful.

{% include links.md %}
