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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 1.8 | 1.01 ± 0.24 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 2.0 | 1.03 ± 0.21 |
| mattcl | input-pting | 1.3 ± 0.1 | 0.4 | 1.8 | 1.05 ± 0.21 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.8 | 1.6 | 1.06 ± 0.22 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.8 | 2.1 | 1.06 ± 0.23 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.8 | 1.8 | 1.07 ± 0.22 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.7 | 2.0 | 1.09 ± 0.23 |
| pting | input-pting | 18.3 ± 0.7 | 16.9 | 21.0 | 14.67 ± 2.51 |
| pting | input-lanjian | 18.5 ± 0.7 | 17.4 | 21.9 | 14.81 ± 2.54 |
| pting | input-mattcl | 18.5 ± 0.8 | 17.4 | 21.4 | 14.82 ± 2.56 |
| pting | input-kcen | 18.6 ± 0.9 | 17.3 | 21.9 | 14.90 ± 2.60 |
| kcen | input-pting | 19.0 ± 0.7 | 18.1 | 22.1 | 15.24 ± 2.61 |
| kcen | input-mattcl | 19.1 ± 0.7 | 17.9 | 21.5 | 15.30 ± 2.62 |
| kcen | input-lanjian | 19.2 ± 0.8 | 17.8 | 22.4 | 15.34 ± 2.65 |
| kcen | input-kcen | 19.2 ± 0.8 | 18.1 | 22.1 | 15.38 ± 2.64 |
| mattcl-py | input-pting | 20.1 ± 0.7 | 18.9 | 23.2 | 16.11 ± 2.75 |
| mattcl-py | input-mattcl | 20.1 ± 0.7 | 18.6 | 23.0 | 16.13 ± 2.75 |
| mattcl-py | input-lanjian | 20.3 ± 0.7 | 19.3 | 23.1 | 16.22 ± 2.77 |
| mattcl-py | input-kcen | 20.3 ± 0.7 | 19.2 | 22.9 | 16.27 ± 2.77 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|