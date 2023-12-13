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
| mattcl | input-pting | 1.0 ± 0.3 | 0.5 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.3 | 0.5 | 1.7 | 1.08 ± 0.46 |
| mattcl | input-mattcl | 1.3 ± 0.4 | 0.6 | 2.0 | 1.26 ± 0.52 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.5 | 2.0 | 1.33 ± 0.45 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.2 | 3.6 | 2.90 ± 0.92 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.2 | 3.6 | 2.96 ± 0.93 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.4 | 4.9 | 3.00 ± 0.93 |
| lanjian | input-mattcl | 3.3 ± 0.3 | 2.8 | 4.1 | 3.18 ± 0.99 |
| mattcl-ts | input-kcen | 17.5 ± 0.5 | 16.5 | 19.1 | 16.88 ± 5.08 |
| mattcl-ts | input-pting | 19.6 ± 7.1 | 17.0 | 61.7 | 18.94 ± 8.86 |
| mattcl-ts | input-lanjian | 20.4 ± 12.2 | 17.1 | 119.5 | 19.64 ± 13.18 |
| mattcl-py | input-kcen | 26.5 ± 1.2 | 24.8 | 33.6 | 25.57 ± 7.75 |
| mattcl-py | input-mattcl | 27.4 ± 0.5 | 26.7 | 29.6 | 26.41 ± 7.93 |
| mattcl-py | input-lanjian | 27.7 ± 0.5 | 26.8 | 29.7 | 26.74 ± 8.03 |
| pting | input-kcen | 29.0 ± 4.4 | 27.7 | 73.4 | 27.95 ± 9.38 |
| pting | input-pting | 29.1 ± 0.7 | 27.7 | 31.5 | 28.12 ± 8.46 |
| pting | input-mattcl | 31.0 ± 1.3 | 29.0 | 34.6 | 29.97 ± 9.07 |
| mattcl-py | input-pting | 34.1 ± 9.5 | 26.8 | 54.9 | 32.88 ± 13.49 |
| mattcl-ts | input-mattcl | 34.6 ± 24.4 | 16.8 | 145.9 | 33.41 ± 25.58 |
| kcen | input-pting | 51.0 ± 1.0 | 49.5 | 54.1 | 49.18 ± 14.78 |
| kcen | input-lanjian | 51.1 ± 0.7 | 50.0 | 53.4 | 49.35 ± 14.81 |
| kcen | input-kcen | 51.6 ± 0.9 | 49.4 | 53.6 | 49.76 ± 14.95 |
| pting | input-lanjian | 64.0 ± 2.6 | 56.0 | 73.6 | 61.73 ± 18.68 |
| kcen | input-mattcl | 133.6 ± 5.6 | 113.0 | 140.7 | 128.89 ± 39.02 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|