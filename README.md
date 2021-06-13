# Logicircuit
https://codepen.io/anisurrahmanlikhon/full/abJQzzy


## Libraries Used:
 EaselJS for display and event models. GSAP for menu animation

## Instructions
1. Drag from an output connection (blue dot) to an input connection (grey dot) to create a wire.
2. You may have multiple wires branch off an output, but only one wire per input.
3. Click a connector (blue or grey dots) to remove all attached wires.
4. Click (+) button in top-right corner to add new circuits.
5. Note that some circuits are interactive


## Circuit Types

### INPUT / OUTPUT
1. IN: A light with an input to turn it on.
2. OUT: Interactive button with an output.

## LOGIC
1. NOT: Outputs inverted input signal.
2. OR: Output is true when any input is true.
3. AND: Output is only true when both inputs are true.
4. XOR: Output is only true when a single input is true.
5. NOR: Output is true when neither input is true.
6. MEM: One bit memory cell that can be switched on/off from inputs, and holds its state.
7. TCK: A set frequency ticker that pulses a single tick signal every `n` ticks (configurable)
8. DLY: Carries a signal after a delay of `n` ticks (configurable)



## TODO:
1. Zooming
2. Instructions / Examples
3.  Improve Import / Export UI
