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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 2.1 | 1.01 ± 0.23 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.8 | 2.0 | 1.07 ± 0.23 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.9 | 2.1 | 1.09 ± 0.22 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 6.0 | 2.37 ± 0.44 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.3 | 5.6 | 2.39 ± 0.44 |
| lanjian | input-pting | 3.1 ± 0.5 | 2.3 | 5.9 | 2.44 ± 0.53 |
| lanjian | input-lanjian | 3.2 ± 0.4 | 2.5 | 6.6 | 2.45 ± 0.49 |
| mattcl-ts | input-mattcl | 17.6 ± 0.4 | 16.6 | 19.0 | 13.61 ± 2.21 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.6 | 19.2 | 13.65 ± 2.22 |
| mattcl-ts | input-kcen | 17.7 ± 0.4 | 16.7 | 19.2 | 13.71 ± 2.23 |
| mattcl-ts | input-lanjian | 18.0 ± 3.0 | 16.7 | 56.2 | 13.94 ± 3.22 |
| mattcl-py | input-kcen | 26.0 ± 1.5 | 24.6 | 40.4 | 20.16 ± 3.45 |
| mattcl-py | input-mattcl | 26.1 ± 0.9 | 24.9 | 29.6 | 20.23 ± 3.33 |
| mattcl-py | input-pting | 26.4 ± 0.9 | 25.0 | 28.9 | 20.42 ± 3.35 |
| mattcl-py | input-lanjian | 27.1 ± 4.9 | 25.5 | 77.7 | 20.95 ± 5.05 |
| pting | input-kcen | 27.2 ± 0.8 | 25.8 | 30.5 | 21.02 ± 3.44 |
| pting | input-mattcl | 27.3 ± 1.1 | 25.6 | 34.2 | 21.11 ± 3.50 |
| pting | input-pting | 27.3 ± 0.8 | 26.1 | 29.9 | 21.11 ± 3.45 |
| pting | input-lanjian | 27.4 ± 0.8 | 26.3 | 30.2 | 21.21 ± 3.46 |
| kcen | input-pting | 47.3 ± 1.0 | 45.4 | 49.9 | 36.58 ± 5.94 |
| kcen | input-lanjian | 48.6 ± 1.1 | 47.0 | 51.5 | 37.60 ± 6.10 |
| kcen | input-kcen | 50.5 ± 1.0 | 48.5 | 52.8 | 39.06 ± 6.33 |
| kcen | input-mattcl | 50.6 ± 1.1 | 48.5 | 53.2 | 39.15 ± 6.35 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|