<div class="cwikmeta" style="visibility:hidden;">
{
"title":"PONG",
"related":["/protocol/network/messages/ping.md"]
} </div>

# Response: Pong ("pong")

Connection keep-alive, "aliveness" and latency discovery.  This message is sent in response to a [PING](/protocol/network/messages/ping.md) message.

## Message Format

| Field | Length | Format | Description |    
|--|--|--|--|  
| nonce | 8 bytes | unsigned 64 bit integer<sup>[(LE)](/protocol/misc/endian/little)</sup>  | The value provided by the [PING](/protocol/network/messages/ping.md) message.
