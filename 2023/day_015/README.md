# Day 15 benchmarks

[link to problem](https://adventofcode.com/2023/day/15)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 15)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-kcen | 1.3 ± 0.2 | 0.6 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.1 | 0.4 | 1.8 | 1.01 ± 0.17 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.6 | 1.9 | 1.01 ± 0.19 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.6 | 1.01 ± 0.19 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.8 | 2.0 | 1.02 ± 0.18 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.6 | 1.9 | 1.02 ± 0.20 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.5 | 1.6 | 1.03 ± 0.20 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.7 | 1.9 | 1.10 ± 0.20 |
| pting | input-pting | 18.4 ± 0.6 | 17.2 | 21.0 | 14.25 ± 1.87 |
| pting | input-lanjian | 18.6 ± 0.7 | 17.4 | 21.9 | 14.40 ± 1.91 |
| pting | input-kcen | 18.7 ± 0.8 | 17.2 | 21.5 | 14.47 ± 1.93 |
| kcen | input-mattcl | 18.9 ± 0.7 | 17.7 | 22.4 | 14.66 ± 1.94 |
| pting | input-mattcl | 19.0 ± 4.1 | 17.4 | 55.8 | 14.71 ± 3.68 |
| kcen | input-lanjian | 19.0 ± 0.7 | 17.9 | 22.8 | 14.73 ± 1.95 |
| kcen | input-pting | 19.0 ± 0.8 | 17.9 | 22.1 | 14.74 ± 1.96 |
| kcen | input-kcen | 19.5 ± 1.2 | 17.8 | 22.8 | 15.11 ± 2.14 |
| mattcl-py | input-mattcl | 20.2 ± 0.7 | 19.1 | 22.9 | 15.65 ± 2.05 |
| mattcl-py | input-pting | 20.2 ± 0.7 | 19.3 | 23.3 | 15.70 ± 2.06 |
| mattcl-py | input-lanjian | 20.3 ± 0.7 | 19.2 | 23.3 | 15.76 ± 2.07 |
| mattcl-py | input-kcen | 20.3 ± 0.7 | 18.9 | 23.3 | 15.77 ± 2.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|