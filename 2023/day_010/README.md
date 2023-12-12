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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 1.7 | 1.01 ± 0.21 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 1.8 | 1.03 ± 0.20 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 2.3 | 1.06 ± 0.23 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.3 | 3.9 | 2.45 ± 0.37 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.7 | 2.46 ± 0.42 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.2 | 5.8 | 2.48 ± 0.44 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.3 | 6.0 | 2.49 ± 0.45 |
| mattcl-ts | input-mattcl | 17.2 ± 0.4 | 16.0 | 18.5 | 13.83 ± 1.99 |
| mattcl-ts | input-pting | 17.3 ± 0.4 | 16.2 | 18.5 | 13.88 ± 1.99 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.2 | 18.4 | 13.89 ± 2.00 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.4 | 18.5 | 13.98 ± 2.01 |
| mattcl-py | input-mattcl | 25.6 ± 0.9 | 24.4 | 28.8 | 20.54 ± 2.99 |
| mattcl-py | input-kcen | 25.6 ± 2.8 | 23.9 | 54.4 | 20.56 ± 3.69 |
| mattcl-py | input-lanjian | 25.8 ± 0.7 | 24.9 | 28.7 | 20.67 ± 2.98 |
| mattcl-py | input-pting | 26.2 ± 0.8 | 25.1 | 28.9 | 20.98 ± 3.05 |
| pting | input-kcen | 26.6 ± 0.9 | 25.3 | 29.6 | 21.35 ± 3.11 |
| pting | input-pting | 26.9 ± 0.8 | 26.0 | 30.1 | 21.57 ± 3.12 |
| pting | input-lanjian | 27.0 ± 0.8 | 25.8 | 30.2 | 21.66 ± 3.13 |
| pting | input-mattcl | 27.1 ± 4.7 | 25.7 | 76.2 | 21.77 ± 4.87 |
| kcen | input-pting | 47.2 ± 1.5 | 45.6 | 52.7 | 37.82 ± 5.48 |
| kcen | input-lanjian | 47.8 ± 0.9 | 46.3 | 50.5 | 38.34 ± 5.48 |
| kcen | input-mattcl | 49.7 ± 0.9 | 47.9 | 52.7 | 39.85 ± 5.69 |
| kcen | input-kcen | 49.9 ± 1.1 | 47.8 | 53.1 | 40.00 ± 5.73 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|