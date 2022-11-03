# Reading

## HTTP ReqRes Cycle

1. Local Processing
  - create query
  - try to resolve ip from local cache
2. Resolve IP - UDP
  - DNS request to get ip sent out
  - bounces around hopefully to find ip
  - passes ip back to client
3. Establish TCP Connection
  - three-way handshake
  - client -> server -> client again
4. Send HTTP Req - TCP
  - end req in numbered packets
  - get res in numbered packets
5. Clean Up
  - four-way goodbye handshake
  - browser processes res

## Java HTTP

- class HttpUrlConnection
- "the code can be ... cumbersome"; surprise
1. make URL object
2. use above class to make connection from via url object
3. 

wow, too much info to take notes like that. This is definitely a bookmark and review resource. I lost it when the tutorial says, if I understood correctly, **build a utility class** to help with query string creation.

Please tell me that spring simplifies this whole process.
