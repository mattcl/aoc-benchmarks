# Day 18 benchmarks

[link to problem](https://adventofcode.com/2023/day/18)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 18)

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-lanjian | 894.0 ± 173.8 | 195.5 | 1165.5 | 1.00 |
| lanjian | input-kcen | 898.9 ± 192.0 | 194.8 | 1106.0 | 1.01 ± 0.29 |
| lanjian | input-pting | 901.7 ± 190.4 | 187.7 | 1704.1 | 1.01 ± 0.29 |
| mattcl | input-mattcl | 931.0 ± 183.4 | 229.6 | 1158.5 | 1.04 ± 0.29 |
| mattcl | input-kcen | 936.4 ± 172.8 | 204.9 | 1160.0 | 1.05 ± 0.28 |
| lanjian | input-mattcl | 938.6 ± 143.2 | 512.4 | 1433.7 | 1.05 ± 0.26 |
| mattcl | input-lanjian | 951.4 ± 174.7 | 372.8 | 1700.7 | 1.06 ± 0.28 |
| mattcl | input-pting | 955.3 ± 132.4 | 526.4 | 1160.8 | 1.07 ± 0.26 |
| mattcl-py | input-pting | 14563.3 ± 718.2 | 13265.5 | 17697.6 | 16.29 ± 3.27 |
| pting | input-pting | 14771.7 ± 614.2 | 13662.0 | 17613.0 | 16.52 ± 3.29 |
| pting | input-lanjian | 14859.0 ± 731.0 | 13834.8 | 18056.5 | 16.62 ± 3.33 |
| mattcl-py | input-kcen | 14880.6 ± 677.5 | 13650.3 | 18277.1 | 16.64 ± 3.32 |
| mattcl-py | input-mattcl | 14910.7 ± 678.2 | 13747.7 | 18539.3 | 16.68 ± 3.33 |
| pting | input-mattcl | 15170.3 ± 562.6 | 14096.8 | 18284.8 | 16.97 ± 3.36 |
| mattcl-py | input-lanjian | 15173.0 ± 5839.5 | 13342.3 | 74266.1 | 16.97 ± 7.32 |
| pting | input-kcen | 15368.2 ± 2494.2 | 14077.0 | 48837.5 | 17.19 ± 4.35 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|