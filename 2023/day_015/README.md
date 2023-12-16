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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.7 | 1.03 ± 0.24 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.4 | 2.2 | 1.04 ± 0.28 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.6 | 1.7 | 1.04 ± 0.24 |
| lanjian | input-lanjian | 1.2 ± 1.5 | 0.3 | 21.6 | 1.05 ± 1.37 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.08 ± 0.24 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.6 | 1.08 ± 0.23 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.09 ± 0.24 |
| pting | input-lanjian | 18.2 ± 0.7 | 17.3 | 21.3 | 16.67 ± 2.93 |
| pting | input-kcen | 18.3 ± 0.8 | 17.3 | 21.2 | 16.71 ± 2.96 |
| pting | input-mattcl | 18.4 ± 0.9 | 17.3 | 22.1 | 16.77 ± 2.98 |
| pting | input-pting | 18.4 ± 1.0 | 17.2 | 22.3 | 16.86 ± 3.03 |
| kcen | input-kcen | 18.6 ± 0.7 | 17.6 | 21.4 | 16.97 ± 2.97 |
| kcen | input-mattcl | 18.6 ± 0.8 | 17.2 | 22.0 | 17.03 ± 3.00 |
| kcen | input-lanjian | 18.7 ± 0.7 | 17.4 | 21.8 | 17.10 ± 3.00 |
| kcen | input-pting | 18.8 ± 0.8 | 17.8 | 22.0 | 17.18 ± 3.04 |
| mattcl-py | input-pting | 20.0 ± 0.6 | 18.8 | 22.9 | 18.24 ± 3.18 |
| mattcl-py | input-kcen | 20.0 ± 0.8 | 18.9 | 22.6 | 18.27 ± 3.21 |
| mattcl-py | input-mattcl | 20.1 ± 0.8 | 18.7 | 23.1 | 18.35 ± 3.22 |
| mattcl-py | input-lanjian | 20.1 ± 2.1 | 18.7 | 44.3 | 18.39 ± 3.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|