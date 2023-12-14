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
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.6 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.9 | 1.02 ± 0.21 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 1.9 | 1.05 ± 0.25 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.3 | 1.9 | 1.08 ± 0.24 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.3 | 3.7 | 2.51 ± 0.40 |
| lanjian | input-pting | 3.1 ± 0.2 | 2.3 | 5.6 | 2.52 ± 0.42 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.3 | 5.6 | 2.52 ± 0.43 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.4 | 6.0 | 2.54 ± 0.44 |
| mattcl-ts | input-kcen | 17.2 ± 0.4 | 16.2 | 18.7 | 14.17 ± 2.14 |
| mattcl-ts | input-mattcl | 17.3 ± 0.4 | 16.3 | 18.5 | 14.19 ± 2.14 |
| mattcl-ts | input-pting | 17.3 ± 0.4 | 16.5 | 18.4 | 14.21 ± 2.14 |
| mattcl-ts | input-lanjian | 18.1 ± 5.7 | 16.5 | 86.0 | 14.86 ± 5.21 |
| mattcl-py | input-kcen | 25.5 ± 0.7 | 24.5 | 29.2 | 20.93 ± 3.18 |
| mattcl-py | input-mattcl | 25.8 ± 0.9 | 24.7 | 29.0 | 21.24 ± 3.25 |
| mattcl-py | input-lanjian | 26.1 ± 0.8 | 24.9 | 29.1 | 21.45 ± 3.27 |
| mattcl-py | input-pting | 26.1 ± 0.8 | 25.1 | 29.4 | 21.46 ± 3.27 |
| pting | input-kcen | 26.6 ± 0.8 | 25.7 | 29.6 | 21.87 ± 3.33 |
| pting | input-mattcl | 26.8 ± 0.7 | 25.9 | 29.3 | 22.06 ± 3.34 |
| pting | input-pting | 27.0 ± 0.7 | 25.8 | 29.8 | 22.21 ± 3.37 |
| pting | input-lanjian | 27.1 ± 0.9 | 25.6 | 29.8 | 22.26 ± 3.40 |
| kcen | input-pting | 47.5 ± 1.2 | 45.6 | 50.4 | 39.05 ± 5.91 |
| kcen | input-lanjian | 47.7 ± 1.0 | 46.2 | 50.7 | 39.25 ± 5.91 |
| kcen | input-mattcl | 50.1 ± 1.2 | 48.4 | 52.8 | 41.21 ± 6.23 |
| kcen | input-kcen | 50.2 ± 1.0 | 48.4 | 52.1 | 41.24 ± 6.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|