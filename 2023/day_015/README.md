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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.3 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.2 | 1.7 | 1.00 ± 0.25 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.5 | 1.6 | 1.00 ± 0.21 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.6 | 1.01 ± 0.21 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.06 ± 0.21 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.3 | 1.7 | 1.07 ± 0.24 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.08 ± 0.23 |
| lanjian | input-kcen | 1.2 ± 0.1 | 0.3 | 1.6 | 1.08 ± 0.20 |
| pting | input-mattcl | 17.9 ± 0.7 | 17.0 | 21.1 | 15.99 ± 2.46 |
| pting | input-kcen | 18.0 ± 0.7 | 16.8 | 22.5 | 16.07 ± 2.48 |
| pting | input-pting | 18.0 ± 0.8 | 17.3 | 22.0 | 16.09 ± 2.51 |
| pting | input-lanjian | 18.1 ± 0.8 | 17.2 | 21.6 | 16.16 ± 2.52 |
| kcen | input-pting | 18.5 ± 0.6 | 17.5 | 21.0 | 16.54 ± 2.52 |
| kcen | input-mattcl | 18.6 ± 0.6 | 17.6 | 21.8 | 16.65 ± 2.54 |
| kcen | input-kcen | 18.6 ± 0.7 | 17.7 | 21.5 | 16.67 ± 2.56 |
| kcen | input-lanjian | 18.7 ± 0.8 | 17.5 | 22.0 | 16.72 ± 2.60 |
| mattcl-py | input-kcen | 19.8 ± 0.6 | 18.5 | 22.3 | 17.70 ± 2.70 |
| mattcl-py | input-lanjian | 19.8 ± 0.7 | 18.8 | 23.4 | 17.71 ± 2.73 |
| mattcl-py | input-mattcl | 19.9 ± 0.8 | 18.9 | 23.2 | 17.77 ± 2.75 |
| mattcl-py | input-pting | 19.9 ± 0.8 | 18.8 | 23.0 | 17.78 ± 2.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|