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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.8 | 1.01 ± 0.21 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.2 | 1.7 | 1.02 ± 0.23 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 2.0 | 1.03 ± 0.21 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.6 | 1.6 | 1.04 ± 0.21 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.6 | 1.05 ± 0.20 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.3 | 1.4 | 1.05 ± 0.21 |
| lanjian | input-lanjian | 1.2 ± 0.1 | 0.6 | 1.6 | 1.06 ± 0.20 |
| pting | input-kcen | 18.3 ± 0.6 | 16.9 | 21.1 | 16.36 ± 2.35 |
| pting | input-pting | 18.3 ± 0.7 | 17.3 | 22.3 | 16.39 ± 2.39 |
| pting | input-lanjian | 18.3 ± 0.8 | 17.2 | 21.4 | 16.42 ± 2.40 |
| pting | input-mattcl | 18.4 ± 0.8 | 17.2 | 21.1 | 16.45 ± 2.41 |
| kcen | input-kcen | 18.8 ± 0.6 | 17.7 | 21.9 | 16.80 ± 2.41 |
| kcen | input-pting | 18.8 ± 0.9 | 17.8 | 22.3 | 16.84 ± 2.48 |
| kcen | input-lanjian | 18.8 ± 0.8 | 17.4 | 21.6 | 16.85 ± 2.46 |
| kcen | input-mattcl | 19.1 ± 3.5 | 17.8 | 57.9 | 17.11 ± 3.93 |
| mattcl-py | input-pting | 20.0 ± 0.8 | 18.8 | 23.1 | 17.86 ± 2.59 |
| mattcl-py | input-lanjian | 20.1 ± 0.7 | 18.9 | 23.2 | 18.03 ± 2.60 |
| mattcl-py | input-kcen | 20.3 ± 3.2 | 18.8 | 57.3 | 18.21 ± 3.81 |
| mattcl-py | input-mattcl | 20.6 ± 4.4 | 19.1 | 58.9 | 18.40 ± 4.71 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|