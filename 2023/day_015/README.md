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
| mattcl | input-pting | 1.0 ± 0.3 | 0.3 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.18 ± 0.40 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.7 | 1.22 ± 0.43 |
| mattcl | input-lanjian | 1.2 ± 0.1 | 0.6 | 1.7 | 1.22 ± 0.41 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.5 | 1.8 | 1.22 ± 0.43 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.7 | 1.7 | 1.22 ± 0.42 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.7 | 1.7 | 1.23 ± 0.42 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.6 | 1.8 | 1.25 ± 0.42 |
| pting | input-lanjian | 18.0 ± 0.7 | 17.0 | 21.7 | 17.55 ± 5.56 |
| pting | input-kcen | 18.0 ± 0.6 | 17.0 | 21.1 | 17.61 ± 5.57 |
| pting | input-mattcl | 18.1 ± 0.8 | 16.8 | 21.0 | 17.66 ± 5.61 |
| kcen | input-mattcl | 18.5 ± 0.6 | 17.4 | 21.4 | 18.06 ± 5.71 |
| pting | input-pting | 18.5 ± 4.4 | 16.9 | 62.7 | 18.06 ± 7.10 |
| kcen | input-pting | 18.6 ± 0.8 | 17.5 | 21.7 | 18.22 ± 5.79 |
| kcen | input-kcen | 18.7 ± 0.7 | 17.9 | 21.7 | 18.29 ± 5.79 |
| kcen | input-lanjian | 18.7 ± 0.8 | 17.7 | 22.2 | 18.31 ± 5.82 |
| mattcl-py | input-mattcl | 19.8 ± 0.7 | 18.7 | 22.6 | 19.32 ± 6.12 |
| mattcl-py | input-lanjian | 19.8 ± 0.6 | 19.1 | 22.3 | 19.34 ± 6.12 |
| mattcl-py | input-kcen | 19.8 ± 0.6 | 18.8 | 22.9 | 19.37 ± 6.12 |
| mattcl-py | input-pting | 19.9 ± 2.0 | 18.8 | 42.0 | 19.50 ± 6.44 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|