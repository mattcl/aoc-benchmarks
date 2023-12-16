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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.00 ± 0.21 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.4 | 1.5 | 1.01 ± 0.21 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.6 | 1.8 | 1.01 ± 0.22 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.8 | 1.02 ± 0.21 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.8 | 1.03 ± 0.23 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.8 | 1.03 ± 0.21 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.4 | 2.0 | 1.04 ± 0.25 |
| pting | input-pting | 18.3 ± 0.6 | 17.4 | 21.5 | 15.09 ± 2.44 |
| pting | input-mattcl | 18.4 ± 0.8 | 17.2 | 21.6 | 15.14 ± 2.48 |
| pting | input-lanjian | 18.4 ± 0.8 | 17.0 | 23.9 | 15.18 ± 2.50 |
| kcen | input-lanjian | 18.7 ± 0.4 | 17.5 | 20.9 | 15.41 ± 2.46 |
| kcen | input-kcen | 18.8 ± 0.7 | 17.6 | 22.0 | 15.47 ± 2.52 |
| kcen | input-pting | 18.8 ± 0.8 | 17.5 | 22.0 | 15.50 ± 2.54 |
| pting | input-kcen | 18.9 ± 2.4 | 17.5 | 42.5 | 15.53 ± 3.16 |
| kcen | input-mattcl | 19.0 ± 2.2 | 17.9 | 45.3 | 15.61 ± 3.07 |
| mattcl-py | input-mattcl | 20.0 ± 0.7 | 18.7 | 22.7 | 16.45 ± 2.66 |
| mattcl-py | input-pting | 20.0 ± 0.6 | 18.6 | 22.2 | 16.50 ± 2.65 |
| mattcl-py | input-kcen | 20.0 ± 0.7 | 18.9 | 23.0 | 16.50 ± 2.66 |
| mattcl-py | input-lanjian | 20.2 ± 0.8 | 19.0 | 23.3 | 16.64 ± 2.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|