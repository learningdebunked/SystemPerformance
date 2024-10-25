# SystemPerformance

** Backend Performance Metrics **


** Front End Performance Metrics **

     ** Load Time ***
     ** Time to first byte(TTFB) **
     ** Request Count **
     ** DOM Content loaded **
     ** Time to above the fold line **
     ** Time to below the fold line **
     ** First Contentful paint(FCP) **
     ** Page size **
     ** Round Trip Time **
     ** Render Blocking Resources **

     ![image](https://github.com/user-attachments/assets/afb79e77-8610-4fcb-b17c-ae3ccf8ab3ed)



![image](https://github.com/learningdebunked/SystemPerformance/assets/7702406/8cd151bb-f7b4-4b9e-aa49-66b74046087a)

Reasons for high CPU

![image](https://github.com/learningdebunked/SystemPerformance/assets/7702406/ea7ac536-a409-4aa9-831e-a65e8c76da96)


**OS Memory structure **

         **  //TODO Know the internals
         ** The operating system reads data from the disk into page cache in kernel space.
         ** The application reads the data from kernel space into a user-space buffer.
         ** The application writes the data back into kernel space into a socket buffer.
         ** The operating system copies the data from the socket buffer to the NIC buffer where it is sent over the network.
         
**RAM structure **

        ** //TODO Know the internals like 

** GC logs **

    ** NMT Logs
    ** Heap space
    ** How to read and debug thread dump


** System load / performance testing **

    ** Types of failures

            ** H/w Failures

                    ** High CPU
                    ** High Memory
                    ** Disk load on container
                    ** 

** ![image](https://github.com/user-attachments/assets/2bb08f27-46e2-47b5-8e03-a67a02653f82)
