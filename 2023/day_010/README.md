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
| mattcl | input-kcen | 1.4 ± 0.2 | 0.8 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.7 | 1.7 | 1.01 ± 0.19 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.8 | 1.8 | 1.01 ± 0.19 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 1.8 | 1.03 ± 0.20 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.2 | 5.6 | 2.26 ± 0.35 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.4 | 5.2 | 2.27 ± 0.36 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.4 | 5.8 | 2.30 ± 0.40 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.5 | 5.8 | 2.31 ± 0.41 |
| mattcl-ts | input-pting | 17.5 ± 0.3 | 16.8 | 18.8 | 12.87 ± 1.78 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.4 | 18.7 | 12.88 ± 1.79 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.6 | 18.7 | 12.89 ± 1.79 |
| mattcl-ts | input-lanjian | 17.7 ± 0.4 | 16.7 | 19.0 | 13.02 ± 1.81 |
| mattcl-py | input-kcen | 25.7 ± 0.9 | 24.3 | 28.8 | 18.86 ± 2.67 |
| mattcl-py | input-mattcl | 26.0 ± 1.4 | 24.5 | 35.1 | 19.11 ± 2.81 |
| mattcl-py | input-pting | 26.1 ± 0.9 | 25.1 | 29.7 | 19.17 ± 2.70 |
| mattcl-py | input-lanjian | 26.4 ± 1.1 | 25.0 | 30.4 | 19.36 ± 2.76 |
| pting | input-mattcl | 27.0 ± 0.8 | 25.5 | 30.3 | 19.83 ± 2.78 |
| pting | input-kcen | 27.1 ± 0.8 | 25.9 | 30.5 | 19.87 ± 2.79 |
| pting | input-lanjian | 27.1 ± 0.8 | 26.0 | 30.5 | 19.93 ± 2.79 |
| pting | input-pting | 27.2 ± 1.0 | 25.6 | 33.2 | 19.95 ± 2.83 |
| kcen | input-pting | 46.9 ± 1.1 | 45.2 | 50.1 | 34.41 ± 4.77 |
| kcen | input-lanjian | 48.3 ± 1.6 | 46.2 | 56.2 | 35.47 ± 5.00 |
| kcen | input-mattcl | 50.0 ± 0.9 | 48.2 | 53.9 | 36.69 ± 5.07 |
| kcen | input-kcen | 50.1 ± 1.0 | 48.3 | 53.0 | 36.80 ± 5.09 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|