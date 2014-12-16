rt-video-processor
==================

Real-time Video Processor Application for LITMUS^RT

An empirical evaluation of deadline driven schedulers on 2 and 4 core multicore systems was performed using a video processing application to generate sporadic real time task sets. The scheduling behavior of Clustered EDF, Partitioned EDF and Global EDF was considered in this evaluation. Overhead traces and scheduling traces were recorded to provide insight into the manner in which this soft real time task set was handled by each of the above schedulers.

For the experiments covered in this paper we have run the evaluations on systems supporting a single processor with multiple cores each. We have used a 2-core Intel Dual core system and a 4-core Intel Core i3 system both running Litmus RT [2]. Litmus RT is a soft real-time extension of the Linux Kernel. Litmus RT makes it convenient to use the various real-time scheduling algorithms as well as synchronization protocols through plugins which can be activated at run-time. The Linux kernel version we are using is 3.10.5 patched with litmus-rt-2014.1.patch.
