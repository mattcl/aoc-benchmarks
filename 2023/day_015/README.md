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
| lanjian | input-pting | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 ± 0.25 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 ± 0.24 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 ± 0.24 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.8 | 1.01 ± 0.24 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.9 | 1.01 ± 0.22 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.7 | 2.0 | 1.03 ± 0.23 |
| lanjian | input-kcen | 1.2 ± 0.1 | 0.8 | 1.7 | 1.04 ± 0.22 |
| pting | input-pting | 17.9 ± 0.6 | 17.1 | 21.0 | 15.04 ± 2.75 |
| pting | input-mattcl | 18.0 ± 0.6 | 17.0 | 20.9 | 15.09 ± 2.75 |
| pting | input-kcen | 18.0 ± 0.7 | 17.0 | 21.5 | 15.12 ± 2.77 |
| pting | input-lanjian | 18.1 ± 0.7 | 17.2 | 21.3 | 15.22 ± 2.79 |
| kcen | input-pting | 18.6 ± 0.7 | 17.4 | 21.7 | 15.58 ± 2.85 |
| kcen | input-mattcl | 18.6 ± 0.8 | 17.3 | 22.2 | 15.62 ± 2.87 |
| kcen | input-lanjian | 18.6 ± 0.6 | 17.5 | 21.3 | 15.63 ± 2.84 |
| kcen | input-kcen | 18.8 ± 0.8 | 17.7 | 22.6 | 15.81 ± 2.91 |
| mattcl-py | input-pting | 19.9 ± 0.7 | 18.9 | 22.7 | 16.70 ± 3.05 |
| mattcl-py | input-kcen | 19.9 ± 0.6 | 19.0 | 22.4 | 16.72 ± 3.03 |
| mattcl-py | input-lanjian | 19.9 ± 0.7 | 18.7 | 23.0 | 16.73 ± 3.05 |
| mattcl-py | input-mattcl | 20.1 ± 2.5 | 18.8 | 48.7 | 16.84 ± 3.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|