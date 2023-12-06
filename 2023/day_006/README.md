# Day 6 benchmarks

[link to problem](https://adventofcode.com/2023/day/6)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 6)

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-lanjian | 674.9 ± 215.3 | 30.2 | 1155.4 | 1.00 |
| mattcl | input-lanjian | 693.8 ± 197.5 | 68.5 | 1031.8 | 1.03 ± 0.44 |
| lanjian | input-pting | 695.5 ± 209.0 | 28.5 | 993.5 | 1.03 ± 0.45 |
| mattcl | input-pting | 725.4 ± 175.7 | 66.6 | 1095.7 | 1.07 ± 0.43 |
| lanjian | input-mattcl | 734.9 ± 140.8 | 135.3 | 1082.5 | 1.09 ± 0.41 |
| mattcl | input-mattcl | 754.9 ± 115.6 | 342.1 | 918.2 | 1.12 ± 0.40 |
| mattcl-ts | input-pting | 9228.8 ± 336.9 | 8187.8 | 10020.2 | 13.67 ± 4.39 |
| mattcl-ts | input-lanjian | 9261.5 ± 345.5 | 8150.7 | 10169.7 | 13.72 ± 4.41 |
| mattcl-ts | input-mattcl | 9280.5 ± 340.8 | 8480.7 | 10475.0 | 13.75 ± 4.41 |
| pting | input-lanjian | 13908.8 ± 435.1 | 13352.7 | 16931.2 | 20.61 ± 6.60 |
| mattcl-py | input-mattcl | 13941.0 ± 539.1 | 12913.7 | 17016.6 | 20.66 ± 6.64 |
| pting | input-pting | 13961.6 ± 591.5 | 13046.5 | 17335.2 | 20.69 ± 6.66 |
| mattcl-py | input-lanjian | 13963.0 ± 578.4 | 13057.7 | 16905.2 | 20.69 ± 6.65 |
| mattcl-py | input-pting | 13996.6 ± 653.8 | 13062.5 | 17713.0 | 20.74 ± 6.69 |
| pting | input-mattcl | 14019.5 ± 654.1 | 12789.6 | 17354.0 | 20.77 ± 6.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|