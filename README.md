# IPFS-Based Ring DHT  

This C++ project implements a **Distributed Hash Table (DHT)** for **InterPlanetary File System (IPFS)** using a **ring-based architecture**. It enables content-addressable file storage and retrieval with efficient distributed lookup.  

## Features  
- Decentralized file storage across multiple machines  
- Content addressing using **SHA-1 hashing**  
- Ring DHT with **circular linked list** for machine management  
- **B-Tree indexing** for efficient file organization  
- Optimized **routing tables** for faster lookups  
- Supports **dynamic machine addition and removal**  

## Commands Supported  
1. **Add a Machine** – Manual or automatic ID assignment  
2. **Delete a Machine** – Transfers files before removal  
3. **Insert a File** – Hashes and stores content correctly  
4. **Search a File** – Uses hashing and routing tables  
5. **Delete a File** – Removes file from the system  
6. **Print Machine B-Tree** – Displays file structure  
7. **Print Machine Routing Table** – Shows routing entries  
8. **Print Active Machines** – Lists all active machines  

## How to Run  
1. Compile and run the project.  
2. Choose system parameters (bits, machines, B-tree order).  
3. Use the interactive menu for file operations.  

## Contributing  
Contributions and improvements are welcome.  

## License  
This project is for educational purposes. Modify as needed.  
