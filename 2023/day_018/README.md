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
| lanjian | input-lanjian | 906.8 ± 169.1 | 194.8 | 1307.3 | 1.00 |
| lanjian | input-pting | 910.1 ± 146.4 | 242.0 | 1118.0 | 1.00 ± 0.25 |
| lanjian | input-mattcl | 910.1 ± 169.7 | 299.9 | 1631.1 | 1.00 ± 0.26 |
| lanjian | input-kcen | 912.7 ± 162.6 | 201.1 | 1343.6 | 1.01 ± 0.26 |
| mattcl | input-pting | 934.5 ± 169.4 | 223.9 | 1461.7 | 1.03 ± 0.27 |
| mattcl | input-kcen | 940.2 ± 174.0 | 235.8 | 1585.6 | 1.04 ± 0.27 |
| mattcl | input-lanjian | 944.6 ± 159.8 | 408.1 | 1430.4 | 1.04 ± 0.26 |
| mattcl | input-mattcl | 962.2 ± 161.0 | 331.1 | 1672.6 | 1.06 ± 0.27 |
| mattcl-py | input-pting | 14535.0 ± 558.0 | 13751.0 | 17387.1 | 16.03 ± 3.05 |
| mattcl-py | input-lanjian | 14575.6 ± 626.4 | 13508.7 | 17938.5 | 16.07 ± 3.08 |
| pting | input-lanjian | 14742.9 ± 658.0 | 13571.7 | 18742.1 | 16.26 ± 3.12 |
| pting | input-pting | 14939.3 ± 738.5 | 13752.7 | 18228.4 | 16.47 ± 3.18 |
| mattcl-py | input-mattcl | 14946.6 ± 583.0 | 13878.5 | 18323.3 | 16.48 ± 3.14 |
| mattcl-py | input-kcen | 14970.9 ± 482.6 | 13903.4 | 17863.3 | 16.51 ± 3.12 |
| pting | input-mattcl | 15068.8 ± 488.2 | 13916.0 | 17809.8 | 16.62 ± 3.14 |
| pting | input-kcen | 15294.0 ± 1770.2 | 13900.3 | 38767.9 | 16.87 ± 3.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|