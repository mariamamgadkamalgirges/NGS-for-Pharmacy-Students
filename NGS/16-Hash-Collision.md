# Hash Collision

## What is a Collision?

A collision occurs when two different keys produce the same hash value.

## Solution

The most common solution is Chaining, where multiple values are stored in the same index.

## Example

Hash("Omar") → Index 9

Hash("Mohamed") → Index 9

Both values are stored together in the same bucket.
