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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.25 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.7 | 1.02 ± 0.25 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 2.0 | 1.06 ± 0.27 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.06 ± 0.25 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.4 | 1.07 ± 0.24 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.07 ± 0.25 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.07 ± 0.25 |
| pting | input-kcen | 18.5 ± 0.7 | 17.5 | 21.3 | 16.40 ± 3.08 |
| pting | input-pting | 18.6 ± 0.8 | 17.4 | 22.0 | 16.46 ± 3.11 |
| kcen | input-kcen | 18.6 ± 0.6 | 17.5 | 21.8 | 16.53 ± 3.09 |
| pting | input-lanjian | 18.7 ± 0.8 | 17.6 | 21.5 | 16.58 ± 3.14 |
| kcen | input-pting | 18.7 ± 0.6 | 17.5 | 21.8 | 16.61 ± 3.10 |
| kcen | input-mattcl | 18.9 ± 0.8 | 17.8 | 21.8 | 16.73 ± 3.16 |
| kcen | input-lanjian | 18.9 ± 0.8 | 17.5 | 22.2 | 16.74 ± 3.17 |
| pting | input-mattcl | 19.5 ± 5.0 | 17.5 | 59.9 | 17.32 ± 5.44 |
| mattcl-py | input-kcen | 20.0 ± 0.8 | 18.9 | 23.9 | 17.78 ± 3.35 |
| mattcl-py | input-lanjian | 20.0 ± 0.7 | 18.9 | 23.4 | 17.78 ± 3.34 |
| mattcl-py | input-mattcl | 20.1 ± 0.8 | 18.5 | 23.3 | 17.85 ± 3.36 |
| mattcl-py | input-pting | 20.2 ± 0.7 | 19.2 | 23.0 | 17.89 ± 3.36 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>511416</pre>|<pre>290779</pre>|
|input-lanjian|<pre>506891</pre>|<pre>230462</pre>|
|input-mattcl|<pre>517015</pre>|<pre>286104</pre>|
|input-pting|<pre>513643</pre>|<pre>265345</pre>|