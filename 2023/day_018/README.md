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

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-pting | 1.0 ± 0.2 | 0.3 | 1.2 | 1.00 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.6 | 1.00 ± 0.26 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.3 | 1.01 ± 0.26 |
| mattcl | input-pting | 1.0 ± 0.1 | 0.4 | 1.2 | 1.04 ± 0.24 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 2.0 | 1.04 ± 0.28 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.2 | 1.05 ± 0.25 |
| lanjian | input-kcen | 1.0 ± 0.1 | 0.3 | 1.6 | 1.05 ± 0.23 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.4 | 1.2 | 1.06 ± 0.24 |
| mattcl-py | input-pting | 14.4 ± 0.6 | 13.4 | 17.3 | 14.99 ± 2.72 |
| mattcl-py | input-lanjian | 14.5 ± 0.6 | 13.4 | 18.4 | 15.06 ± 2.72 |
| pting | input-pting | 14.6 ± 0.6 | 13.6 | 17.7 | 15.24 ± 2.75 |
| mattcl-py | input-mattcl | 14.9 ± 0.7 | 13.9 | 18.1 | 15.49 ± 2.81 |
| pting | input-lanjian | 14.9 ± 1.4 | 13.8 | 32.2 | 15.51 ± 3.07 |
| mattcl-py | input-kcen | 15.0 ± 0.7 | 13.9 | 18.1 | 15.60 ± 2.84 |
| pting | input-mattcl | 15.2 ± 0.5 | 14.3 | 17.7 | 15.78 ± 2.83 |
| pting | input-kcen | 15.2 ± 0.6 | 14.0 | 17.9 | 15.81 ± 2.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|