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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.23 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.9 | 1.02 ± 0.25 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 2.0 | 1.04 ± 0.23 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.5 | 1.04 ± 0.21 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.6 | 2.0 | 1.05 ± 0.23 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.6 | 1.7 | 1.06 ± 0.22 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.9 | 1.08 ± 0.23 |
| pting | input-mattcl | 18.5 ± 0.9 | 17.4 | 21.6 | 15.37 ± 2.63 |
| pting | input-lanjian | 18.6 ± 0.7 | 17.6 | 22.1 | 15.42 ± 2.60 |
| pting | input-kcen | 18.6 ± 0.9 | 17.4 | 22.3 | 15.48 ± 2.66 |
| pting | input-pting | 18.7 ± 3.1 | 17.5 | 56.4 | 15.51 ± 3.62 |
| kcen | input-mattcl | 18.9 ± 0.8 | 17.5 | 22.0 | 15.67 ± 2.65 |
| kcen | input-pting | 18.9 ± 0.8 | 17.7 | 22.3 | 15.68 ± 2.66 |
| kcen | input-kcen | 18.9 ± 0.6 | 18.0 | 21.7 | 15.71 ± 2.64 |
| kcen | input-lanjian | 19.0 ± 0.8 | 17.7 | 22.1 | 15.76 ± 2.68 |
| mattcl-py | input-mattcl | 20.1 ± 0.6 | 18.8 | 22.7 | 16.67 ± 2.78 |
| mattcl-py | input-kcen | 20.2 ± 0.8 | 18.7 | 23.0 | 16.76 ± 2.83 |
| mattcl-py | input-lanjian | 20.2 ± 0.7 | 18.8 | 23.7 | 16.80 ± 2.83 |
| mattcl-py | input-pting | 20.3 ± 0.8 | 19.2 | 23.2 | 16.83 ± 2.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|