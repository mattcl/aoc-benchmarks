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
| lanjian | input-pting | 1.0 ± 0.2 | 0.4 | 1.8 | 1.00 |
| lanjian | input-lanjian | 1.0 ± 0.1 | 0.5 | 1.2 | 1.01 ± 0.24 |
| mattcl | input-lanjian | 1.1 ± 0.1 | 0.5 | 1.3 | 1.03 ± 0.24 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.5 | 1.6 | 1.03 ± 0.24 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.6 | 1.8 | 1.03 ± 0.24 |
| lanjian | input-mattcl | 1.1 ± 0.1 | 0.6 | 1.3 | 1.04 ± 0.23 |
| mattcl | input-pting | 1.1 ± 0.1 | 0.5 | 1.2 | 1.05 ± 0.22 |
| mattcl | input-kcen | 1.1 ± 0.1 | 0.5 | 1.2 | 1.05 ± 0.24 |
| mattcl-py | input-pting | 14.7 ± 0.5 | 13.9 | 18.0 | 14.23 ± 2.71 |
| mattcl-py | input-lanjian | 14.8 ± 0.6 | 13.9 | 18.0 | 14.34 ± 2.74 |
| pting | input-pting | 15.0 ± 0.7 | 13.7 | 18.1 | 14.52 ± 2.80 |
| pting | input-lanjian | 15.1 ± 0.5 | 14.2 | 17.9 | 14.56 ± 2.77 |
| mattcl-py | input-kcen | 15.1 ± 0.5 | 14.2 | 18.5 | 14.64 ± 2.79 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.2 | 18.1 | 14.67 ± 2.80 |
| pting | input-mattcl | 15.3 ± 0.6 | 14.3 | 18.5 | 14.84 ± 2.84 |
| pting | input-kcen | 15.5 ± 0.7 | 14.5 | 18.9 | 14.96 ± 2.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|