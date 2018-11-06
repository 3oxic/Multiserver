# Multiserver
A server handling multiple client's with select()
![alt text](http://i65.tinypic.com/1ru8ex.jpg)

Main accepts new connections and sets them to the set. Each of the threads in the fugure above will call select, and will "listen" if any of the file descriptors in the set is written.
