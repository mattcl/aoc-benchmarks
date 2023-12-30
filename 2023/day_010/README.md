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
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.7 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.5 ± 0.2 | 0.9 | 2.0 | 1.01 ± 0.18 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 0.7 | 2.1 | 1.03 ± 0.20 |
| mattcl | input-pting | 1.5 ± 0.2 | 0.9 | 3.0 | 1.06 ± 0.21 |
| lanjian | input-pting | 3.2 ± 0.2 | 2.5 | 5.0 | 2.21 ± 0.34 |
| lanjian | input-kcen | 3.2 ± 0.2 | 2.6 | 4.9 | 2.22 ± 0.34 |
| lanjian | input-mattcl | 3.2 ± 0.4 | 2.6 | 5.9 | 2.24 ± 0.40 |
| lanjian | input-lanjian | 3.3 ± 0.4 | 2.6 | 6.1 | 2.28 ± 0.40 |
| mattcl-ts | input-mattcl | 17.6 ± 0.4 | 16.5 | 18.8 | 12.19 ± 1.62 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.6 | 18.9 | 12.20 ± 1.62 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.4 | 19.0 | 12.23 ± 1.63 |
| mattcl-ts | input-lanjian | 17.8 ± 0.5 | 16.9 | 19.3 | 12.32 ± 1.64 |
| mattcl-py | input-kcen | 25.8 ± 1.0 | 24.6 | 29.7 | 17.89 ± 2.43 |
| mattcl-py | input-mattcl | 26.1 ± 0.8 | 25.0 | 29.3 | 18.07 ± 2.43 |
| mattcl-py | input-pting | 26.5 ± 0.8 | 25.1 | 29.4 | 18.34 ± 2.47 |
| mattcl-py | input-lanjian | 26.5 ± 0.9 | 24.9 | 30.0 | 18.36 ± 2.48 |
| pting | input-kcen | 27.2 ± 1.0 | 26.0 | 30.5 | 18.87 ± 2.55 |
| pting | input-mattcl | 27.2 ± 0.8 | 25.7 | 30.3 | 18.89 ± 2.53 |
| pting | input-lanjian | 27.4 ± 0.8 | 26.0 | 30.3 | 18.99 ± 2.54 |
| pting | input-pting | 27.4 ± 0.7 | 26.4 | 30.5 | 19.01 ± 2.54 |
| kcen | input-pting | 47.5 ± 1.2 | 45.7 | 50.2 | 32.95 ± 4.38 |
| kcen | input-lanjian | 48.5 ± 1.1 | 46.9 | 51.1 | 33.63 ± 4.46 |
| kcen | input-mattcl | 50.7 ± 1.3 | 48.9 | 56.2 | 35.12 ± 4.68 |
| kcen | input-kcen | 50.7 ± 1.5 | 48.6 | 58.0 | 35.15 ± 4.71 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|