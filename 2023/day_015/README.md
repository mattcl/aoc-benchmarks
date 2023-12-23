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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.1 | 0.6 | 1.6 | 1.00 ± 0.17 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.6 | 1.6 | 1.00 ± 0.19 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.01 ± 0.21 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.2 | 2.6 | 1.01 ± 0.22 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.20 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 2.0 | 1.02 ± 0.21 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 2.0 | 1.06 ± 0.24 |
| pting | input-mattcl | 18.1 ± 0.6 | 17.1 | 21.1 | 15.86 ± 2.19 |
| pting | input-pting | 18.2 ± 0.8 | 16.8 | 21.4 | 15.90 ± 2.25 |
| pting | input-lanjian | 18.3 ± 0.9 | 17.4 | 22.1 | 16.04 ± 2.28 |
| pting | input-kcen | 18.4 ± 0.7 | 17.4 | 21.8 | 16.09 ± 2.25 |
| kcen | input-pting | 18.7 ± 0.6 | 17.9 | 21.6 | 16.32 ± 2.26 |
| kcen | input-lanjian | 18.8 ± 0.7 | 17.6 | 21.9 | 16.43 ± 2.29 |
| kcen | input-mattcl | 18.8 ± 0.8 | 17.4 | 22.1 | 16.48 ± 2.32 |
| kcen | input-kcen | 18.9 ± 0.8 | 17.5 | 21.9 | 16.53 ± 2.33 |
| mattcl-py | input-mattcl | 19.9 ± 0.8 | 18.5 | 23.2 | 17.44 ± 2.44 |
| mattcl-py | input-pting | 20.0 ± 0.7 | 18.9 | 22.9 | 17.46 ± 2.42 |
| mattcl-py | input-lanjian | 20.0 ± 0.7 | 18.9 | 22.6 | 17.51 ± 2.43 |
| mattcl-py | input-kcen | 20.1 ± 0.7 | 19.0 | 22.9 | 17.58 ± 2.44 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|