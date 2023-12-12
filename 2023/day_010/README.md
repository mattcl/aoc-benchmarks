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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.4 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.21 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.7 | 2.0 | 1.03 ± 0.20 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.0 | 1.13 ± 0.24 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.3 | 5.6 | 2.54 ± 0.41 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.3 | 5.7 | 2.55 ± 0.42 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.3 | 5.5 | 2.56 ± 0.44 |
| lanjian | input-lanjian | 3.1 ± 0.4 | 2.2 | 5.7 | 2.59 ± 0.50 |
| mattcl-ts | input-kcen | 17.5 ± 0.4 | 16.5 | 18.8 | 14.86 ± 2.13 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.6 | 18.7 | 14.90 ± 2.13 |
| mattcl-ts | input-mattcl | 17.6 ± 0.4 | 16.3 | 18.8 | 14.90 ± 2.14 |
| mattcl-ts | input-lanjian | 17.7 ± 0.4 | 16.6 | 19.7 | 15.01 ± 2.15 |
| mattcl-py | input-kcen | 25.7 ± 0.8 | 24.5 | 28.7 | 21.81 ± 3.15 |
| mattcl-py | input-mattcl | 25.8 ± 0.7 | 24.5 | 29.1 | 21.91 ± 3.16 |
| mattcl-py | input-lanjian | 26.1 ± 0.9 | 24.7 | 29.8 | 22.16 ± 3.23 |
| mattcl-py | input-pting | 26.1 ± 0.9 | 24.5 | 29.2 | 22.19 ± 3.23 |
| pting | input-kcen | 27.0 ± 0.9 | 25.4 | 29.8 | 22.90 ± 3.32 |
| pting | input-mattcl | 27.0 ± 0.7 | 25.8 | 29.9 | 22.96 ± 3.29 |
| pting | input-lanjian | 27.1 ± 0.8 | 25.8 | 30.0 | 23.02 ± 3.32 |
| pting | input-pting | 27.2 ± 0.8 | 26.1 | 30.3 | 23.07 ± 3.32 |
| kcen | input-pting | 47.4 ± 1.1 | 45.6 | 50.4 | 40.26 ± 5.76 |
| kcen | input-lanjian | 47.9 ± 1.0 | 46.3 | 50.7 | 40.68 ± 5.81 |
| kcen | input-mattcl | 50.1 ± 1.2 | 48.2 | 53.2 | 42.49 ± 6.09 |
| kcen | input-kcen | 50.2 ± 1.0 | 48.2 | 53.4 | 42.65 ± 6.09 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|