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

AT THE SENDER GUI:

![image](https://github.com/infinitycni2312/Implementation-of-Go-Back-N-ARQ-Protocol/assets/127985606/f8543e66-fc9a-4a94-b5c8-775d04d9e8cc)

AT THE RECEIVER GUI:

![image](https://github.com/infinitycni2312/Implementation-of-Go-Back-N-ARQ-Protocol/assets/127985606/e56d2eff-fcc4-4cdc-955c-4f1d76cdccb2)

<hr><hr>

<br><br>
