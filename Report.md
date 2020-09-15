Task 0: Set up 

I used git to clone the forked 2020-sensor-miniproject repository from the senior design github group to my computer. 
Once I did that, I ran into a few errors in trying to run this command: python -m pip install -e 2020-sensor-miniproject. 
I was using git bash and I tried cygwin as different compilers, but I always ran into the "permission denied" error. Finally, it worked
after I ran it using the regular cmd prompt from windows. 

After the installation was done, I was able to run python -m sp_iotsim.server and python -m sp_iotsim.client. 
The initial greeting I received was: "IoT server starting:  localhost port 8765" by the server to the client after it connected. 

Task 1: data flow

