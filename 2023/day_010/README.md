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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.5 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.20 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.01 ± 0.20 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 2.8 | 1.05 ± 0.23 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.3 | 5.9 | 2.48 ± 0.41 |
| lanjian | input-lanjian | 3.0 ± 0.3 | 2.3 | 5.7 | 2.48 ± 0.43 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.6 | 5.8 | 2.49 ± 0.43 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.2 | 5.8 | 2.50 ± 0.47 |
| mattcl-ts | input-mattcl | 17.5 ± 0.5 | 16.3 | 18.7 | 14.23 ± 2.05 |
| mattcl-ts | input-pting | 17.5 ± 0.4 | 16.7 | 18.8 | 14.30 ± 2.04 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.7 | 18.6 | 14.32 ± 2.05 |
| mattcl-ts | input-lanjian | 17.7 ± 0.4 | 16.3 | 18.6 | 14.40 ± 2.06 |
| mattcl-py | input-mattcl | 25.6 ± 0.8 | 24.5 | 29.0 | 20.89 ± 3.02 |
| mattcl-py | input-kcen | 25.7 ± 0.8 | 24.6 | 28.8 | 20.98 ± 3.03 |
| mattcl-py | input-pting | 26.0 ± 0.7 | 24.9 | 29.1 | 21.23 ± 3.05 |
| mattcl-py | input-lanjian | 26.3 ± 0.9 | 24.9 | 29.4 | 21.43 ± 3.12 |
| pting | input-kcen | 27.0 ± 0.8 | 25.5 | 29.6 | 22.03 ± 3.19 |
| pting | input-lanjian | 27.1 ± 0.7 | 25.9 | 29.9 | 22.10 ± 3.18 |
| pting | input-pting | 27.2 ± 0.8 | 26.1 | 30.4 | 22.20 ± 3.20 |
| pting | input-mattcl | 27.3 ± 0.8 | 26.1 | 30.2 | 22.27 ± 3.22 |
| kcen | input-pting | 47.6 ± 1.1 | 45.9 | 50.4 | 38.81 ± 5.55 |
| kcen | input-lanjian | 48.4 ± 1.3 | 46.4 | 52.4 | 39.47 ± 5.67 |
| kcen | input-kcen | 50.2 ± 1.2 | 48.1 | 52.9 | 40.92 ± 5.86 |
| kcen | input-mattcl | 50.3 ± 1.2 | 48.6 | 53.0 | 41.05 ± 5.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|