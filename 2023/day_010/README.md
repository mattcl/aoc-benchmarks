# Day 10 benchmarks

[link to problem](https://adventofcode.com/2023/day/10)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 10)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-kcen | 1.8 ± 0.2 | 0.9 | 2.2 | 1.00 |
| mattcl | input-mattcl | 1.8 ± 0.2 | 0.9 | 2.3 | 1.00 ± 0.18 |
| mattcl | input-lanjian | 1.9 ± 0.2 | 1.0 | 2.2 | 1.04 ± 0.16 |
| lanjian | input-lanjian | 3.1 ± 0.1 | 2.3 | 3.5 | 1.72 ± 0.23 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.3 | 5.0 | 1.72 ± 0.25 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.6 | 1.73 ± 0.28 |
| mattcl-ts | input-mattcl | 16.7 ± 0.5 | 15.7 | 18.6 | 9.32 ± 1.23 |
| mattcl-ts | input-kcen | 16.8 ± 0.4 | 15.8 | 18.6 | 9.35 ± 1.22 |
| mattcl-ts | input-lanjian | 16.9 ± 0.5 | 15.9 | 18.5 | 9.42 ± 1.24 |
| mattcl-py | input-kcen | 38.8 ± 1.0 | 37.4 | 41.5 | 21.62 ± 2.83 |
| mattcl-py | input-mattcl | 38.9 ± 0.9 | 37.7 | 42.2 | 21.70 ± 2.84 |
| mattcl-py | input-lanjian | 39.6 ± 0.9 | 38.2 | 41.9 | 22.06 ± 2.87 |
| kcen | input-lanjian | 93.5 ± 1.5 | 91.7 | 99.9 | 52.12 ± 6.75 |
| kcen | input-mattcl | 94.5 ± 1.7 | 92.3 | 100.2 | 52.67 ± 6.83 |
| kcen | input-kcen | 95.0 ± 5.6 | 91.9 | 124.7 | 52.95 ± 7.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|