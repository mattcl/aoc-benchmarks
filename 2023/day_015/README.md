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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.7 | 1.01 ± 0.21 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.6 | 1.8 | 1.03 ± 0.20 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.7 | 2.0 | 1.05 ± 0.22 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.7 | 2.1 | 1.06 ± 0.22 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.7 | 1.06 ± 0.21 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.7 | 1.9 | 1.09 ± 0.21 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.8 | 2.0 | 1.12 ± 0.21 |
| pting | input-mattcl | 18.2 ± 0.6 | 17.4 | 21.3 | 15.39 ± 2.25 |
| pting | input-lanjian | 18.3 ± 0.7 | 17.0 | 21.1 | 15.49 ± 2.29 |
| pting | input-kcen | 18.3 ± 0.7 | 17.2 | 21.7 | 15.51 ± 2.29 |
| pting | input-pting | 18.4 ± 1.0 | 17.0 | 21.8 | 15.59 ± 2.37 |
| kcen | input-lanjian | 18.8 ± 0.7 | 17.6 | 22.0 | 15.92 ± 2.35 |
| kcen | input-pting | 18.8 ± 0.7 | 17.8 | 21.6 | 15.93 ± 2.34 |
| kcen | input-mattcl | 18.8 ± 0.7 | 17.9 | 22.5 | 15.94 ± 2.35 |
| kcen | input-kcen | 18.8 ± 0.6 | 17.9 | 22.0 | 15.96 ± 2.33 |
| mattcl-py | input-kcen | 19.9 ± 0.6 | 18.8 | 22.6 | 16.86 ± 2.46 |
| mattcl-py | input-pting | 19.9 ± 0.7 | 18.7 | 22.9 | 16.90 ± 2.48 |
| mattcl-py | input-mattcl | 20.0 ± 0.8 | 18.6 | 22.9 | 16.95 ± 2.50 |
| mattcl-py | input-lanjian | 20.1 ± 0.8 | 18.9 | 23.1 | 17.04 ± 2.53 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|