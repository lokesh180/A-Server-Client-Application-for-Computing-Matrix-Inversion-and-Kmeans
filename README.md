# A-Server-Client-Application-for-Computing-Matrix-Inversion-and-Kmeans

This main aim of this project is to implement a client and server architecture using fork for multiple cilents.
When the Client has exited with SIGINT(CTRL+C), the server should not create zombie processes and server should shows that particular client is exited.
The Server need to run the commands, which were provided by client and return the output for client.
The client is responsible for providing execution commands for two programs with its parameters.

Those two programs were Matrix Inversion and Kmeans. These programs were implemented by using pthreads.
The load is balanced by multiple threads and the technique used is Data Parallelism.
The Zip file with all contents was uploded.
