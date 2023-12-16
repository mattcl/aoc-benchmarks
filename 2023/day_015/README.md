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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.4 | 1.6 | 1.00 ± 0.27 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.6 | 1.6 | 1.05 ± 0.24 |
| mattcl | input-pting | 1.1 ± 0.1 | 0.5 | 1.6 | 1.05 ± 0.24 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.07 ± 0.27 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.5 | 1.7 | 1.09 ± 0.25 |
| lanjian | input-pting | 1.2 ± 0.1 | 0.4 | 1.7 | 1.11 ± 0.24 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.12 ± 0.26 |
| pting | input-kcen | 18.0 ± 0.6 | 16.9 | 21.5 | 16.60 ± 3.14 |
| pting | input-pting | 18.0 ± 0.7 | 16.9 | 21.4 | 16.62 ± 3.16 |
| pting | input-lanjian | 18.3 ± 2.3 | 17.1 | 45.8 | 16.93 ± 3.82 |
| kcen | input-pting | 18.6 ± 0.7 | 17.6 | 21.7 | 17.20 ± 3.27 |
| kcen | input-lanjian | 18.7 ± 0.6 | 17.9 | 21.4 | 17.23 ± 3.26 |
| kcen | input-mattcl | 18.7 ± 0.7 | 17.6 | 21.9 | 17.24 ± 3.27 |
| kcen | input-kcen | 18.7 ± 0.6 | 17.7 | 21.3 | 17.24 ± 3.26 |
| pting | input-mattcl | 18.7 ± 5.1 | 16.9 | 58.5 | 17.25 ± 5.67 |
| mattcl-py | input-kcen | 19.8 ± 0.7 | 18.5 | 22.6 | 18.30 ± 3.46 |
| mattcl-py | input-pting | 19.8 ± 0.8 | 18.7 | 22.7 | 18.31 ± 3.49 |
| mattcl-py | input-lanjian | 20.0 ± 0.9 | 19.0 | 23.2 | 18.43 ± 3.52 |
| mattcl-py | input-mattcl | 20.1 ± 2.7 | 18.7 | 44.7 | 18.56 ± 4.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|