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
| mattcl | input-lanjian | 1.8 ± 0.2 | 0.9 | 2.3 | 1.00 |
| mattcl | input-mattcl | 1.8 ± 0.2 | 1.1 | 2.3 | 1.01 ± 0.16 |
| mattcl | input-kcen | 1.8 ± 0.2 | 1.0 | 2.3 | 1.01 ± 0.17 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.2 | 3.7 | 1.71 ± 0.23 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.2 | 5.8 | 1.72 ± 0.26 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.4 | 4.8 | 1.73 ± 0.24 |
| mattcl-ts | input-mattcl | 16.8 ± 0.4 | 15.8 | 18.1 | 9.38 ± 1.15 |
| mattcl-ts | input-kcen | 16.9 ± 0.4 | 16.0 | 18.0 | 9.45 ± 1.16 |
| mattcl-ts | input-lanjian | 17.7 ± 6.2 | 15.9 | 87.1 | 9.88 ± 3.67 |
| mattcl-py | input-kcen | 38.8 ± 1.0 | 37.4 | 41.5 | 21.67 ± 2.68 |
| mattcl-py | input-mattcl | 39.0 ± 1.2 | 37.4 | 44.0 | 21.78 ± 2.70 |
| mattcl-py | input-lanjian | 39.7 ± 0.9 | 38.5 | 42.6 | 22.14 ± 2.71 |
| kcen | input-lanjian | 93.2 ± 1.1 | 91.3 | 95.3 | 51.98 ± 6.30 |
| kcen | input-mattcl | 94.4 ± 1.3 | 91.5 | 97.3 | 52.68 ± 6.40 |
| kcen | input-kcen | 95.0 ± 5.4 | 92.2 | 123.4 | 53.00 ± 7.07 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|