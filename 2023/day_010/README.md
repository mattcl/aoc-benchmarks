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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.6 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.7 | 1.6 | 1.02 ± 0.20 |
| mattcl | input-lanjian | 1.2 ± 0.1 | 0.7 | 1.7 | 1.03 ± 0.20 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.9 | 1.05 ± 0.23 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.2 | 5.7 | 2.56 ± 0.43 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.2 | 5.6 | 2.57 ± 0.45 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.2 | 5.5 | 2.58 ± 0.48 |
| lanjian | input-lanjian | 3.0 ± 0.3 | 2.3 | 5.6 | 2.60 ± 0.48 |
| mattcl-ts | input-mattcl | 17.2 ± 0.4 | 16.2 | 18.5 | 14.68 ± 2.22 |
| mattcl-ts | input-kcen | 17.2 ± 0.4 | 16.2 | 18.4 | 14.71 ± 2.22 |
| mattcl-ts | input-pting | 17.3 ± 0.4 | 16.4 | 18.4 | 14.77 ± 2.23 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.2 | 18.5 | 14.83 ± 2.25 |
| mattcl-py | input-kcen | 25.4 ± 0.9 | 24.0 | 27.9 | 21.68 ± 3.32 |
| mattcl-py | input-mattcl | 25.5 ± 0.7 | 24.2 | 28.5 | 21.77 ± 3.31 |
| mattcl-py | input-pting | 26.0 ± 0.9 | 24.8 | 29.1 | 22.20 ± 3.41 |
| pting | input-kcen | 26.6 ± 0.9 | 25.7 | 29.5 | 22.73 ± 3.48 |
| pting | input-mattcl | 26.8 ± 0.8 | 25.5 | 29.6 | 22.89 ± 3.49 |
| pting | input-lanjian | 26.9 ± 0.8 | 25.8 | 30.5 | 22.97 ± 3.50 |
| mattcl-py | input-lanjian | 26.9 ± 5.9 | 24.8 | 60.9 | 23.03 ± 6.13 |
| pting | input-pting | 26.9 ± 0.8 | 26.0 | 29.9 | 23.03 ± 3.51 |
| kcen | input-pting | 46.9 ± 1.1 | 45.5 | 49.8 | 40.11 ± 6.06 |
| kcen | input-lanjian | 47.9 ± 1.1 | 46.3 | 50.9 | 40.95 ± 6.19 |
| kcen | input-mattcl | 49.8 ± 1.1 | 48.3 | 52.8 | 42.57 ± 6.42 |
| kcen | input-kcen | 49.9 ± 1.1 | 47.9 | 52.8 | 42.69 ± 6.44 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|