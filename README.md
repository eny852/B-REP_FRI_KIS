# B-REP_FRI_KIS

B-REP is a Fast ReRoute mechanism implemented in discrete simulator OMNeT++. This repository contains source files which contains additional algorithm for B-REP implementation. The modified files are: IPv4, OSPFRouter, OSPFRouting. Besides source files, repository contains testing topology.

# How to setup this project
1. Download OMNeT++ version 5.0 -> [Omnet++ 5.0](https://omnetpp.org/download/old.html)
2. Copy the OMNeT++ archive to the directory where you want to install it. Choose a
directory whose full path does not contain any space; for example, do not put OMNeT++ under Program Files
3. Extract the zip file
4. Start mingwenv.cmd
5. Enter the following commands into console:
  ```
  $ ./configure
  $ make
  ```
The build process will create both debug and release binaries
  
6. Download [AnsaInet 3.4.0](https://ansa.omnetpp.org/)
7. Extract AnsaInet into OMNeT++ folder
8. Download src.zip and DynamicTest-Enhanced_MREP from this github repository
9. Extract src.zip into C:\omnetpp-5.0\ANSA-ansainet-3.4.0\src and overwrite all the files
10. Extract DynamicTest-Enhanced_MREP into C:\omnetpp-5.0\ANSA-ansainet-3.4.0\examples\ospfv2 
11. Enter the following command into console:
  ```
  $ omnetpp
  ```
  
Command will start OMNeT++

12. In the top left menu select File > Import
    - In import window select General > Existing Projects into Workspace
    - In Select root directory navigate to your OMNeT++ folder
    - After search for projects is complete click on Finish
