# Answers

## 1.4

**In how many blocks is the ran-dom_words1.tar file divided? In which DataNodes is block 2 of this file located?**

It is divided into 7 blocks. Block 2 is available at:

- datanode3
- datanode4
- datanode2


The NameNode/DataNodes run with the ARM-compatible setup, while the TimelineServer uses the AMD64 image under Docker emulation because the ARM distribution lacked the required LevelDB JNI native library. The TimelineServer uses the shared Hadoop configuration volume.
