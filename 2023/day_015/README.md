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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.00 ± 0.21 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.6 | 1.6 | 1.03 ± 0.20 |
| lanjian | input-kcen | 1.2 ± 0.1 | 0.7 | 1.5 | 1.04 ± 0.20 |
| mattcl | input-kcen | 1.2 ± 2.4 | 0.2 | 34.4 | 1.05 ± 2.05 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.7 | 1.7 | 1.05 ± 0.22 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.6 | 2.3 | 1.05 ± 0.23 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.7 | 2.0 | 1.06 ± 0.21 |
| pting | input-pting | 18.4 ± 0.7 | 17.3 | 21.1 | 15.81 ± 2.41 |
| pting | input-mattcl | 18.4 ± 0.8 | 17.3 | 21.4 | 15.85 ± 2.44 |
| pting | input-kcen | 18.6 ± 0.9 | 17.3 | 21.4 | 16.02 ± 2.49 |
| kcen | input-kcen | 18.8 ± 0.5 | 17.7 | 21.8 | 16.17 ± 2.43 |
| kcen | input-pting | 18.8 ± 0.7 | 17.7 | 22.1 | 16.17 ± 2.46 |
| kcen | input-lanjian | 18.9 ± 0.6 | 17.9 | 21.4 | 16.25 ± 2.47 |
| pting | input-lanjian | 18.9 ± 4.2 | 17.0 | 55.9 | 16.29 ± 4.37 |
| kcen | input-mattcl | 19.2 ± 4.0 | 17.8 | 67.0 | 16.53 ± 4.21 |
| mattcl-py | input-pting | 20.0 ± 0.7 | 18.9 | 23.4 | 17.24 ± 2.62 |
| mattcl-py | input-mattcl | 20.1 ± 0.9 | 18.6 | 23.4 | 17.31 ± 2.67 |
| mattcl-py | input-lanjian | 20.2 ± 0.8 | 19.3 | 23.6 | 17.38 ± 2.66 |
| mattcl-py | input-kcen | 20.2 ± 0.7 | 18.9 | 23.2 | 17.40 ± 2.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|