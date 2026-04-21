# Multiplexing

Multiplexing is the set of techniques that allows the simultaneous transmission of multiple signals across a single data link.

<p align="center">
  <img src="images/4.1.1.png"><br>
  <em>Figure 4.1.1: Dividing a link into channels</em>
</p>

In a multiplexed system, `n` lines share the bandwidth of one link. _Figure 4.1.1_ shows the basic format of a multiplexed system. The lines on the left direct their transmission streams to a multiplexer (MUX), which combines them into a single stream (many-to-one). At the receiving end, that stream is fed into a demultiplexer (DEMUX), which separates the stream back into its component transmissions (one-to-many) and directs them to their corresponding lines. In the figure, the word link refers to the physical path. The word channel refers to the portion of a link that carries a transmission between a given pair of lines. One link can have many `(n)` channels.

There are three basic multiplexing techniques:

- Frequency-division multiplexing,
- Wavelength-division multiplexing, and
- Time-division multiplexing

```mermaid
graph TD
    Multiplexing --> Frequency-division multiplexing
    Multiplexing --> Wavelength-division multiplexing
    Multiplexing --> Time-division multiplexing
```
