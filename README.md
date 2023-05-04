Download Link: https://assignmentchef.com/product/solved-csc458-%e2%80%90-problem-set-2-ps2
<br>
Submit a <strong>PDF</strong> document on MarkUs (https://markus.teach.cs.toronto.edu/csc458‐2018‐

09/?locale=en).  The filename should be ps2.pdf.  Ensure you have your name and student number on your PS2.  No submission 48 hours after the due date is accepted.  Show your work if you want partial marks in case your answer is not completely correct.




<ol>

 <li>Consider the network shown below, in which horizontal lines represent transit providers and numbered vertical lines are inter‐provider links.

  <ol>

   <li>How many routes to P could provider Q’s BGP receive?</li>

   <li>Suppose Q and P adopt the policy that outbound traffic is routed to the closest link to the destination’s provider, thus minimizing their own cost. What paths will traffic from host A to host B and from host B to host A take?</li>

  </ol></li>

</ol>




<ol start="2">

 <li>Suppose most of the Internet used some form of geographical addressing, but that a large international organization has a single IP network address and routes its internal traffic over its own links.

  <ol>

   <li>Explain the routing inefficiency for the organization’s inbound traffic inherent in this situation.</li>

   <li>Explain how the organization might solve this problem for outbound traffic.</li>

   <li>For your method above to work for inbound traffic, what would have to happen?</li>

   <li>Suppose the large organization now changes its addressing to separate geographical addresses for each office. What will its internal routing structure have to look like if internal traffic is still to be routed internally?</li>

  </ol></li>

 <li>The sequence number field in the TCP header is 32 bits long, which is big enough to cover over 4 billion bytes of data. Even if this many bytes were never transferred over a single connection, why might the sequence number still wrap around from 2<sup>32</sup> −1 to 0?</li>

</ol>




<ol start="4">

 <li>Suppose a TCP connection has a window size of eight segments and an RTT of 800 ms, the sender sends segments at a regular rate of one every 100 ms, and the receiver sends ACKs back at the same rate without delay. A segment is lost, and the loss is detected by the fast retransmit algorithm on the receipt of the third duplicate ACK. At the point when the ACK of the retransmitted segment finally arrives, how much total time has the sender lost (compared to lossless transmission) if the sender waits for the ACK from the retransmitted lost packet before sliding the window forward again?</li>

</ol>




<ol start="5">

 <li>You are an Internet Service Provider; your client hosts connect directly to your routers. You know some hosts are using experimental TCPs and suspect some may be using a “greedy” TCP with no congestion control. What measurements might you make at your router to establish that a client was not using slow start at all? If a client used slow start on startup but not after a timeout, could you detect that?</li>

 <li>Consider the arrangement of hosts H and routers R and R1 below. All links are full‐duplex, and all routers are faster than their links.  Show that R1 cannot become congested, and for any other router R we can find a traffic pattern that congests that router alone.</li>

</ol>







<ol start="7">

 <li>Suppose Client A initiates a Telnet session with Server S. At about the same time, Client B also initiates a Telnet session with Server S. Provide possible source and destination port numbers for a) The segments send from A to S

  <ol>

   <li>The segments sent from B to S</li>

   <li>The segments sent from S to A</li>

   <li>The segments sent from S to B</li>

   <li>If A and B are different hosts, is it possible that the source port number in the segments from A to S is the same as that from B to S?</li>

   <li>How about if they are the same host?</li>

  </ol></li>

</ol>




<ol start="8">

 <li>UDP and TCP use 1s complement for their checksums. Suppose you have the following three 8‐bit bytes: 01010011, 01100110, 01110100.  What is the 1s complement of the sum of these 8‐bit bytes? (Note that although UDP and TCP use 16‐bit words in computing the checksum, for this problem you are being asked to consider 8‐bit sums.)  Show all work.  Why is it that UDP takes the 1s complement of the sum; that is, why not just use the sum?  With the 1s complement scheme, how does the receiver detect errors? Is it possible that a 1‐bit error will go undetected?  How about a 2‐bit error?</li>

 <li>Consider sending a large file from a host to another over a TCP connection that has no loss.

  <ol>

   <li>Suppose TCP uses AIMD for its congestion control without slow start. Assuming cwnd increases by 1 MSS every time a batch of ACKs is received and assuming approximately constant round‐trip times, how long does it take for cwnd to increase from 6 MSS to 12</li>

  </ol></li>

</ol>

MSS (assuming no loss events)?

<ol>

 <li>What is the average throughout (in terms of MSS and RTT) for this connection up through time = 6 RTT?</li>

</ol>

<ol start="10">

 <li>Consider the network shown below. Suppose AS3 and AS2 are running OSPF for their intra‐AS routing protocol. Suppose AS1 and AS4 are running RIP for their intra‐AS routing protocol. Suppose eBGP and iBGP are used for the inter‐AS routing protocol. Initially suppose there is no physical link between AS2 and AS4.

  <ol>

   <li>Router 3c learns about prefix x from which routing protocol: OSPF, RIP, eBGP, or iBGP?</li>

   <li>Router 3a learns about x from which routing protocol?</li>

   <li>Router 1c learns about x from which routing protocol?</li>

   <li>Router 1d learns about x from which routing protocol?</li>

  </ol></li>

</ol>







<ol start="11">

 <li>Consider the following network. With the indicated link costs, use Dijkstra’s shortest‐path algorithm to compute the shortest path from x to all network nodes.</li>

</ol>




<ol start="12">

 <li>Consider transferring an enormous file of L bytes from Host A to Host B. Assume an MSS of 536 bytes.

  <ol>

   <li>What is the maximum value of L such that TCP sequence numbers are not exhausted?</li>

   <li>Recall that the TCP sequence number field has 4 bytes. For the L you obtain in (a), find how long it takes to transmit the file.  Assume that a total of 66 bytes of transport, network, and data‐link header are added to each segment before the resulting packet is sent out over a 155 Mbps link. Ignore flow control and congestion control so A can pump out the segments back to back and continuously.</li>

  </ol></li>

</ol>




<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>