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
| lanjian | input-pting | 1.0 ± 0.2 | 0.2 | 1.4 | 1.00 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.5 | 1.6 | 1.01 ± 0.25 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.4 | 1.5 | 1.01 ± 0.26 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.9 | 1.02 ± 0.28 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.4 | 1.6 | 1.02 ± 0.25 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.5 | 1.5 | 1.06 ± 0.25 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.5 | 1.5 | 1.07 ± 0.26 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.09 ± 0.26 |
| mattcl-py | input-pting | 14.7 ± 0.6 | 13.6 | 18.5 | 14.94 ± 2.89 |
| mattcl-py | input-lanjian | 14.8 ± 0.7 | 13.7 | 17.6 | 15.11 ± 2.94 |
| pting | input-pting | 15.0 ± 0.7 | 14.0 | 18.0 | 15.26 ± 2.97 |
| pting | input-lanjian | 15.0 ± 0.6 | 13.9 | 17.8 | 15.29 ± 2.95 |
| mattcl-py | input-kcen | 15.2 ± 0.6 | 13.8 | 18.0 | 15.47 ± 2.98 |
| mattcl-py | input-mattcl | 15.2 ± 0.7 | 13.8 | 18.1 | 15.52 ± 3.02 |
| pting | input-kcen | 15.3 ± 0.6 | 14.1 | 18.3 | 15.59 ± 3.01 |
| pting | input-mattcl | 15.4 ± 0.7 | 14.3 | 18.4 | 15.68 ± 3.06 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|