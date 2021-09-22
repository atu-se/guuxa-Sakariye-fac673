# Student README

## Questions

1. The client and server have different sized buffers.  Why does it still work?
server doesnt care about client buffer

2. What happens if the buffer size on the client is changed to a value smaller than the initial `message_length`?
message divede into letters
3. What happens if you run the client when the server is not running? 
there  is connection error
4. What happens if you run the server while the server is already running?
there is os error
5. What changes did you make to finish this assignment?
changes server.py  running while loop from accepting from the connection and added if in for the password 
   and replacing if to elif
6. What resources did you use to complete this assignemnt?  Make a Markdown list of web links below.
youtube links 