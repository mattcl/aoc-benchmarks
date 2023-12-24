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
| lanjian | input-mattcl | 960.1 ± 182.9 | 304.6 | 1290.5 | 1.00 |
| lanjian | input-lanjian | 988.0 ± 149.2 | 242.3 | 1181.5 | 1.03 ± 0.25 |
| lanjian | input-pting | 994.3 ± 136.5 | 568.1 | 1183.9 | 1.04 ± 0.24 |
| mattcl | input-pting | 1024.5 ± 170.5 | 299.1 | 1742.6 | 1.07 ± 0.27 |
| mattcl | input-lanjian | 1031.8 ± 166.7 | 296.3 | 1513.1 | 1.07 ± 0.27 |
| mattcl | input-mattcl | 1036.4 ± 158.1 | 349.0 | 1756.1 | 1.08 ± 0.26 |
| mattcl-py | input-lanjian | 14581.9 ± 591.8 | 13521.9 | 17859.0 | 15.19 ± 2.96 |
| mattcl-py | input-pting | 14602.8 ± 654.9 | 13784.6 | 18602.1 | 15.21 ± 2.98 |
| pting | input-lanjian | 14809.8 ± 668.3 | 13716.6 | 18174.7 | 15.43 ± 3.02 |
| pting | input-pting | 14894.4 ± 701.2 | 13693.5 | 17993.6 | 15.51 ± 3.04 |
| pting | input-mattcl | 15352.2 ± 1760.6 | 14157.5 | 38667.5 | 15.99 ± 3.56 |
| mattcl-py | input-mattcl | 15554.0 ± 3635.0 | 14077.8 | 52544.5 | 16.20 ± 4.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|