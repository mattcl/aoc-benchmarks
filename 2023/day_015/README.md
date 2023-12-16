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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.01 ± 0.23 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.22 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.8 | 1.02 ± 0.22 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.4 | 1.04 ± 0.23 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.9 | 1.10 ± 0.24 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.7 | 1.9 | 1.10 ± 0.23 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.7 | 2.0 | 1.12 ± 0.28 |
| pting | input-pting | 18.2 ± 0.7 | 17.0 | 22.0 | 15.69 ± 2.70 |
| pting | input-mattcl | 18.3 ± 0.6 | 17.0 | 20.9 | 15.71 ± 2.69 |
| pting | input-lanjian | 18.4 ± 0.8 | 17.0 | 21.8 | 15.83 ± 2.74 |
| pting | input-kcen | 18.4 ± 0.7 | 17.0 | 21.2 | 15.84 ± 2.73 |
| kcen | input-lanjian | 18.7 ± 0.6 | 17.9 | 21.7 | 16.13 ± 2.77 |
| kcen | input-mattcl | 18.8 ± 0.7 | 17.9 | 21.8 | 16.14 ± 2.79 |
| kcen | input-pting | 18.8 ± 0.7 | 17.9 | 21.4 | 16.14 ± 2.78 |
| kcen | input-kcen | 18.8 ± 0.7 | 17.6 | 22.1 | 16.18 ± 2.80 |
| mattcl-py | input-kcen | 20.0 ± 0.6 | 19.0 | 22.6 | 17.19 ± 2.94 |
| mattcl-py | input-lanjian | 20.1 ± 0.7 | 18.5 | 22.7 | 17.25 ± 2.97 |
| mattcl-py | input-pting | 20.1 ± 0.7 | 19.0 | 23.0 | 17.26 ± 2.97 |
| mattcl-py | input-mattcl | 20.1 ± 0.8 | 19.1 | 23.3 | 17.30 ± 2.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|