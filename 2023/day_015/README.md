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
| mattcl | input-pting | 1.1 ± 0.2 | 0.6 | 1.6 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.2 | 1.6 | 1.01 ± 0.22 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.4 | 1.4 | 1.02 ± 0.22 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.8 | 1.03 ± 0.23 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.4 | 1.04 ± 0.21 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 2.0 | 1.04 ± 0.24 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.04 ± 0.21 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.05 ± 0.22 |
| pting | input-pting | 18.2 ± 0.6 | 17.1 | 21.1 | 16.41 ± 2.53 |
| pting | input-mattcl | 18.2 ± 0.6 | 17.0 | 21.2 | 16.44 ± 2.53 |
| pting | input-lanjian | 18.3 ± 0.8 | 17.0 | 21.4 | 16.45 ± 2.57 |
| pting | input-kcen | 18.5 ± 0.9 | 17.3 | 22.1 | 16.70 ± 2.64 |
| kcen | input-pting | 18.8 ± 0.8 | 17.7 | 23.2 | 16.91 ± 2.64 |
| kcen | input-lanjian | 18.8 ± 0.7 | 17.7 | 21.7 | 16.96 ± 2.62 |
| kcen | input-mattcl | 18.8 ± 0.9 | 17.3 | 21.8 | 16.97 ± 2.67 |
| kcen | input-kcen | 18.9 ± 0.8 | 17.5 | 22.3 | 17.03 ± 2.66 |
| mattcl-py | input-mattcl | 20.0 ± 0.6 | 18.9 | 23.2 | 17.97 ± 2.75 |
| mattcl-py | input-pting | 20.0 ± 0.6 | 18.6 | 22.6 | 17.98 ± 2.76 |
| mattcl-py | input-lanjian | 20.2 ± 0.8 | 18.8 | 22.7 | 18.16 ± 2.82 |
| mattcl-py | input-kcen | 20.2 ± 0.8 | 19.0 | 23.5 | 18.21 ± 2.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|