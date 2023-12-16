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
| mattcl | input-lanjian | 1.0 ± 0.3 | 0.2 | 1.7 | 1.00 |
| lanjian | input-lanjian | 1.1 ± 0.3 | 0.3 | 1.7 | 1.03 ± 0.39 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.06 ± 0.33 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.5 | 1.06 ± 0.32 |
| mattcl | input-pting | 1.1 ± 0.1 | 0.3 | 1.6 | 1.09 ± 0.32 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.5 | 1.6 | 1.15 ± 0.35 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.6 | 1.17 ± 0.35 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.18 ± 0.35 |
| pting | input-mattcl | 17.9 ± 0.6 | 17.0 | 21.0 | 17.48 ± 4.66 |
| pting | input-lanjian | 18.0 ± 0.6 | 17.1 | 21.4 | 17.54 ± 4.68 |
| pting | input-kcen | 18.0 ± 0.8 | 17.0 | 21.4 | 17.57 ± 4.71 |
| pting | input-pting | 18.4 ± 2.6 | 16.9 | 44.3 | 17.96 ± 5.37 |
| kcen | input-mattcl | 18.5 ± 0.6 | 17.4 | 21.0 | 18.06 ± 4.81 |
| kcen | input-lanjian | 18.6 ± 0.8 | 17.7 | 21.7 | 18.18 ± 4.87 |
| kcen | input-pting | 18.6 ± 0.7 | 17.5 | 21.9 | 18.18 ± 4.86 |
| kcen | input-kcen | 18.7 ± 0.8 | 17.6 | 21.9 | 18.21 ± 4.87 |
| mattcl-py | input-pting | 19.8 ± 0.7 | 18.7 | 23.2 | 19.30 ± 5.15 |
| mattcl-py | input-kcen | 19.8 ± 0.7 | 18.8 | 22.6 | 19.30 ± 5.15 |
| mattcl-py | input-mattcl | 19.8 ± 0.8 | 18.8 | 22.5 | 19.34 ± 5.18 |
| mattcl-py | input-lanjian | 19.9 ± 0.8 | 18.6 | 22.9 | 19.43 ± 5.20 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|