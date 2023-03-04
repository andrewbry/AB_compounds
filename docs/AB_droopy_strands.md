# `droopy_strands`

Creates strands between mulitple sets of positions.
Added options for sequential connections and basic swinging animation.

## Inputs

### `positions_from`
An array of positions that the strands will connect from.

### `positions_to`
An array of positions that the strands will connect to.

## Input Options

### `droop_min`
Minimum amount of possible droop.

### `droop_max`
Maximum amount of possible droop.

### `droop_bias`
0 all strands have the minimum droop.
1 all strands have maximum droop.

### `curvature_slope`
0 strand trough widens
1 default shape

### `max_connections`
This is good for the sequential option. It will iterate to max number of from positions.

### `strand_count`
Determins maximum amound of strands to be created.

### `strand_samples`
How many samples the strands can have.

### `random_seed`
Random seed value to control connections and min-max drooping order.

### `sequential_order`
Check this to sequential connect between the from and to positions. Good for things like power lines.

### `animate`
Check this to turn on a simple swinging motion based off a sine wave.

### `swing_frequency`
Frequency of the sine wave.

### `swing_magnitude`
Magnitude of the sine wave.

### `seed`
Seed value to change random sine wave timing offset.

## Outputs

### `out_points`
This is an 2D array each index holding the points for each strand.

### `strands`
The output strands as one object. Has an orientation for instancing capabilities.
