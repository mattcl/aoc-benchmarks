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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.7 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.5 | 1.7 | 1.01 ± 0.22 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.7 | 1.03 ± 0.22 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 1.9 | 1.04 ± 0.23 |
| lanjian | input-pting | 3.0 ± 0.1 | 2.4 | 3.8 | 2.42 ± 0.41 |
| lanjian | input-lanjian | 3.0 ± 0.2 | 2.5 | 5.6 | 2.42 ± 0.43 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.3 | 4.8 | 2.42 ± 0.42 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.3 | 4.7 | 2.43 ± 0.43 |
| mattcl-ts | input-mattcl | 17.0 ± 0.5 | 15.8 | 18.7 | 13.62 ± 2.22 |
| mattcl-ts | input-pting | 17.0 ± 0.4 | 16.0 | 18.2 | 13.63 ± 2.21 |
| mattcl-ts | input-kcen | 17.1 ± 0.4 | 16.2 | 18.3 | 13.69 ± 2.21 |
| mattcl-ts | input-lanjian | 17.3 ± 0.5 | 16.1 | 18.6 | 13.80 ± 2.24 |
| mattcl-py | input-kcen | 25.8 ± 1.0 | 24.3 | 29.7 | 20.66 ± 3.41 |
| mattcl-py | input-mattcl | 25.9 ± 0.9 | 24.6 | 28.9 | 20.70 ± 3.39 |
| mattcl-py | input-pting | 26.0 ± 0.8 | 24.8 | 30.6 | 20.82 ± 3.40 |
| mattcl-py | input-lanjian | 26.2 ± 1.0 | 24.7 | 29.6 | 20.99 ± 3.46 |
| pting | input-kcen | 27.1 ± 0.8 | 25.9 | 30.4 | 21.65 ± 3.53 |
| pting | input-mattcl | 27.2 ± 0.8 | 26.0 | 30.0 | 21.77 ± 3.54 |
| pting | input-pting | 27.3 ± 0.8 | 26.2 | 30.1 | 21.87 ± 3.55 |
| pting | input-lanjian | 27.3 ± 0.9 | 26.2 | 31.2 | 21.88 ± 3.57 |
| kcen | input-pting | 47.5 ± 1.1 | 45.6 | 51.5 | 37.99 ± 6.15 |
| kcen | input-lanjian | 48.2 ± 1.0 | 46.2 | 50.9 | 38.52 ± 6.22 |
| kcen | input-kcen | 50.3 ± 1.2 | 48.5 | 53.0 | 40.26 ± 6.51 |
| kcen | input-mattcl | 50.6 ± 1.1 | 48.6 | 53.5 | 40.49 ± 6.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|