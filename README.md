# VM

this topic aims at how to create and manage a VM, and config the VM network, and protect its storage infra. VM can provide high availability for Hyper-V env by implementing failover clustering (故障移轉的叢集).

# Server Virtualization

* to enable a physical pc(Host) to run multi-OS (PCs)

* Host Server (a.k.a VM host) share resoures with all VM.

* to allow to detach pc hosting a sevice from the hardware it is running on.

* all the server workload can run on VM.

* to share resources to VM and reduce the physically deployment.

# Virtual Desktop

* Client-Side

  it allows user to run virtualization instance of ready-to-go os and apps.

* VDI, (Interface)

 1) it reduces hardware cost.
 
 2) user can run their app and access data on the VM  from any other devices that support "Remote Desktop Client Software"

# Basic:

TCP/IP, Network

Storage Infra (Replica)

Bash/Powershell

Lib obj & Lib

Cloud

Service

------------------------------------------------------------------

# Main Steps:

(1) Evaluation of Env

(2) Install VM 

(3) Create VM and its vHard Disk

(4) Create its Network and config it

(5) Storage Infra Replica

(6) Failover Clustering

(7) Cloud

(8) Service

(9) Monitor
