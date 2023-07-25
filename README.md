# <center> Implementation-of-Go-Back-N-ARQ-Protocol

<br><br>

<hr> 

## GO-BACK-N Protocol

Go-Back-N protocol, also called Go-Back-N Automatic Repeat reQuest.It is a data link layer protocol that uses a sliding window method for reliable and sequential delivery of data frames. It sends multiple frames before receiving the acknowledgment for the first frame. The frames are sequentially numbered and have a finite number of frames. It can transmit N frames to the peer before requiring an acknowledgment(ACK).


<br><br>

<hr>

## Working principle :
Out-of-Order packets are not accepted(discarded) and the entire window is re-transmitted as there is a receiver buffer. Hence the Go-Back-N protocol controls error and flow of the data 
packets from sender to receiver.


## Output :

![image](https://github.com/infinitycni2312/Implementation-of-Go-Back-N-ARQ-Protocol/assets/127985606/c0fe4a7c-c7e5-4a44-8208-fe8699ddfe03)


<hr><hr>

<br><br>
