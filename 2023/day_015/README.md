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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.6 | 1.00 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.6 | 1.7 | 1.01 ± 0.20 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.22 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 2.0 | 1.01 ± 0.21 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 2.1 | 1.04 ± 0.22 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.5 | 1.04 ± 0.20 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.7 | 1.5 | 1.05 ± 0.19 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.7 | 1.7 | 1.05 ± 0.21 |
| pting | input-kcen | 18.5 ± 0.7 | 17.3 | 21.9 | 15.55 ± 2.23 |
| pting | input-pting | 18.5 ± 0.8 | 17.3 | 21.4 | 15.55 ± 2.24 |
| pting | input-mattcl | 18.5 ± 0.8 | 17.1 | 21.6 | 15.59 ± 2.27 |
| pting | input-lanjian | 18.6 ± 0.8 | 17.6 | 21.8 | 15.64 ± 2.27 |
| kcen | input-pting | 18.8 ± 0.6 | 17.6 | 21.4 | 15.80 ± 2.24 |
| kcen | input-mattcl | 19.0 ± 0.7 | 17.7 | 22.2 | 15.97 ± 2.28 |
| kcen | input-lanjian | 19.0 ± 0.7 | 17.9 | 21.6 | 15.97 ± 2.29 |
| kcen | input-kcen | 19.0 ± 0.7 | 18.0 | 21.9 | 16.02 ± 2.29 |
| mattcl-py | input-lanjian | 20.1 ± 0.6 | 19.3 | 23.0 | 16.96 ± 2.40 |
| mattcl-py | input-pting | 20.2 ± 0.7 | 18.8 | 23.0 | 16.97 ± 2.42 |
| mattcl-py | input-kcen | 20.2 ± 0.6 | 19.0 | 23.9 | 16.99 ± 2.41 |
| mattcl-py | input-mattcl | 20.3 ± 0.6 | 19.0 | 22.5 | 17.05 ± 2.41 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|