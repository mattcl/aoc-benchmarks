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
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.4 | 1.5 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.8 | 1.6 | 1.00 ± 0.20 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.4 | 2.0 | 1.00 ± 0.22 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.8 | 1.9 | 1.09 ± 0.22 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.8 | 2.43 ± 0.43 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.4 | 5.6 | 2.43 ± 0.39 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.3 | 6.1 | 2.43 ± 0.44 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.5 | 5.7 | 2.45 ± 0.42 |
| mattcl-ts | input-mattcl | 17.3 ± 0.4 | 16.3 | 18.4 | 13.64 ± 2.00 |
| mattcl-ts | input-pting | 17.4 ± 0.4 | 16.4 | 18.5 | 13.69 ± 2.01 |
| mattcl-ts | input-kcen | 17.4 ± 0.4 | 16.4 | 18.7 | 13.70 ± 2.01 |
| mattcl-ts | input-lanjian | 17.5 ± 0.4 | 16.7 | 18.5 | 13.75 ± 2.02 |
| mattcl-py | input-kcen | 25.5 ± 0.7 | 24.5 | 28.3 | 20.04 ± 2.96 |
| mattcl-py | input-mattcl | 25.6 ± 0.7 | 24.6 | 28.2 | 20.18 ± 2.98 |
| mattcl-py | input-lanjian | 26.0 ± 0.7 | 24.9 | 28.7 | 20.43 ± 3.01 |
| mattcl-py | input-pting | 26.1 ± 0.9 | 24.9 | 30.0 | 20.55 ± 3.06 |
| pting | input-kcen | 26.9 ± 1.0 | 25.6 | 30.2 | 21.16 ± 3.17 |
| pting | input-lanjian | 27.1 ± 1.0 | 25.9 | 30.4 | 21.36 ± 3.19 |
| pting | input-pting | 27.2 ± 0.8 | 26.1 | 29.9 | 21.41 ± 3.16 |
| pting | input-mattcl | 27.3 ± 3.6 | 26.0 | 64.6 | 21.48 ± 4.23 |
| kcen | input-pting | 47.6 ± 3.6 | 45.7 | 73.4 | 37.45 ± 6.12 |
| kcen | input-lanjian | 47.9 ± 1.5 | 46.1 | 54.1 | 37.71 ± 5.58 |
| kcen | input-kcen | 50.1 ± 0.9 | 48.7 | 52.4 | 39.47 ± 5.77 |
| kcen | input-mattcl | 50.5 ± 1.6 | 48.6 | 60.1 | 39.72 ± 5.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|