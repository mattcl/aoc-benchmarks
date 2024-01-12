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
| mattcl | input-mattcl | 1.1 ± 0.3 | 0.3 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.13 ± 0.34 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 1.7 | 1.14 ± 0.34 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.7 | 1.15 ± 0.35 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.4 | 2.1 | 1.19 ± 0.37 |
| lanjian | input-mattcl | 1.3 ± 2.4 | 0.3 | 34.1 | 1.19 ± 2.26 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.6 | 1.9 | 1.20 ± 0.36 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.7 | 2.0 | 1.21 ± 0.37 |
| pting | input-pting | 17.9 ± 0.6 | 16.9 | 21.0 | 17.06 ± 4.61 |
| pting | input-lanjian | 18.0 ± 0.6 | 17.3 | 21.4 | 17.12 ± 4.63 |
| pting | input-mattcl | 18.0 ± 0.8 | 17.1 | 20.9 | 17.16 ± 4.66 |
| pting | input-kcen | 18.1 ± 0.6 | 17.2 | 21.4 | 17.21 ± 4.65 |
| kcen | input-mattcl | 18.6 ± 0.6 | 17.7 | 21.3 | 17.66 ± 4.76 |
| kcen | input-pting | 18.6 ± 0.7 | 17.5 | 21.5 | 17.69 ± 4.79 |
| kcen | input-kcen | 18.8 ± 0.7 | 17.6 | 21.5 | 17.84 ± 4.83 |
| kcen | input-lanjian | 18.8 ± 0.8 | 17.6 | 21.8 | 17.86 ± 4.85 |
| mattcl-py | input-pting | 19.8 ± 0.7 | 18.7 | 22.3 | 18.85 ± 5.10 |
| mattcl-py | input-kcen | 20.0 ± 0.7 | 18.8 | 23.1 | 19.00 ± 5.14 |
| mattcl-py | input-mattcl | 20.0 ± 0.9 | 18.7 | 23.4 | 19.01 ± 5.17 |
| mattcl-py | input-lanjian | 20.1 ± 2.6 | 18.6 | 43.6 | 19.15 ± 5.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|