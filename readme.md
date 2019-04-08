<h2> Problem Statement</h2>

1. Implementation of LSR based on k-best neighbor flooding (A node floods its LSP only to k min cost neighbors; not to all neighbors). Each LSP must contain Node ID, Seq No, TTL and cost vector. The protocol must be tested with suitable test cases considering >k neighbors for some node. Freshness and consistency of flooding process must be tested with appropriate test cases.

2. Implementation of Distance Vector Routing with poison inverse for count-to-infinity problem. Each node will compute DV every t seconds and send the same to its neighbors. Introduce topology changes (including change of link cost or failure of link) randomly. You can use your own implementation of timer (example: counter based). The topology changes may be introduced at any random value of the timer. Use appropriate test cases for validation of your implementation. 

3. Implementation of DNS look up.

4. Implementation of Selective Repeat ARQ protocol. 
