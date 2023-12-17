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
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.4 | 2.2 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 2.2 | 1.01 ± 0.24 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.5 | 2.0 | 1.02 ± 0.22 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.8 | 2.2 | 1.05 ± 0.22 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.3 | 5.3 | 2.33 ± 0.42 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.4 | 5.7 | 2.33 ± 0.41 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.3 | 6.0 | 2.37 ± 0.49 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.4 | 5.7 | 2.39 ± 0.45 |
| mattcl-ts | input-pting | 17.2 ± 0.4 | 16.2 | 18.4 | 13.15 ± 2.09 |
| mattcl-ts | input-mattcl | 17.2 ± 0.4 | 16.2 | 18.9 | 13.15 ± 2.09 |
| mattcl-ts | input-kcen | 17.2 ± 0.4 | 15.9 | 18.3 | 13.20 ± 2.10 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.2 | 18.7 | 13.30 ± 2.12 |
| mattcl-py | input-kcen | 25.6 ± 0.8 | 23.9 | 28.8 | 19.60 ± 3.14 |
| mattcl-py | input-mattcl | 25.8 ± 0.8 | 24.0 | 29.1 | 19.76 ± 3.17 |
| mattcl-py | input-pting | 26.2 ± 1.0 | 24.5 | 29.4 | 20.04 ± 3.25 |
| mattcl-py | input-lanjian | 26.2 ± 1.0 | 25.1 | 29.4 | 20.08 ± 3.24 |
| pting | input-kcen | 27.1 ± 0.9 | 25.6 | 30.3 | 20.76 ± 3.34 |
| pting | input-pting | 27.2 ± 0.8 | 26.1 | 30.7 | 20.84 ± 3.33 |
| pting | input-lanjian | 27.2 ± 0.8 | 26.2 | 30.2 | 20.84 ± 3.33 |
| pting | input-mattcl | 27.3 ± 0.8 | 26.2 | 30.6 | 20.87 ± 3.33 |
| kcen | input-pting | 47.3 ± 1.2 | 45.8 | 52.7 | 36.22 ± 5.77 |
| kcen | input-lanjian | 48.5 ± 1.1 | 46.8 | 51.1 | 37.14 ± 5.89 |
| kcen | input-mattcl | 50.3 ± 1.3 | 48.5 | 55.9 | 38.47 ± 6.12 |
| kcen | input-kcen | 50.7 ± 1.1 | 49.1 | 53.5 | 38.85 ± 6.16 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|