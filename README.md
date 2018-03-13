代码来自linux-2.6.11.1,除注释外不做任何修改.

## 注释过的文件

* include
    * linux
        * fs.h
        * radis-tree.h
        * dcache.h
        * file.h
        * fs_struct.h
        * sched.h
        * mm.h
        * mmzone.h
        * gfp.h
        * slab.h
	* net.h
    * asm-alpha
        * page.h
    * asm-i386
        * io.h
        * page.h
    * net
	* sock.h
* fs  
    * select.c
    * read_write.c
    * eventpoll.c
    * sysfs
	* bin.c
* lib
    * radix-tree.c
* mm
    * filemap.c
    * mmap.c
    * slab.c
* kernel
    * fork.c
* net
    * socket.c
    * ipv4
	* af_inet.c
	* udp.c




## 特别重要的文件

* net/ipv4/af_inet.c,IPV4下的TCP和UDP socket的相关操作都在里面,包括bind等.

* fs/eventpoll.c,epoll机制全在里面。



整个项目有```300MB+```,感觉愧对github...
