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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 2.0 | 1.00 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.5 | 2.0 | 1.01 ± 0.25 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.7 | 1.8 | 1.02 ± 0.23 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.2 | 1.08 ± 0.26 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.3 | 6.2 | 2.38 ± 0.48 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 4.8 | 2.38 ± 0.48 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.6 | 2.39 ± 0.48 |
| lanjian | input-kcen | 3.1 ± 0.4 | 2.1 | 5.7 | 2.39 ± 0.52 |
| mattcl-ts | input-mattcl | 17.2 ± 0.4 | 16.1 | 18.8 | 13.43 ± 2.43 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.3 | 18.6 | 13.43 ± 2.43 |
| mattcl-ts | input-pting | 17.3 ± 0.4 | 16.2 | 18.5 | 13.49 ± 2.44 |
| mattcl-ts | input-lanjian | 17.5 ± 0.4 | 16.4 | 18.6 | 13.59 ± 2.46 |
| mattcl-py | input-kcen | 25.4 ± 0.9 | 24.4 | 28.8 | 19.75 ± 3.61 |
| mattcl-py | input-mattcl | 25.7 ± 1.0 | 24.6 | 31.4 | 20.03 ± 3.68 |
| mattcl-py | input-lanjian | 26.0 ± 0.9 | 24.5 | 29.4 | 20.27 ± 3.71 |
| mattcl-py | input-pting | 26.1 ± 1.0 | 24.9 | 29.2 | 20.35 ± 3.73 |
| pting | input-kcen | 26.7 ± 0.8 | 25.6 | 29.5 | 20.78 ± 3.78 |
| pting | input-lanjian | 26.9 ± 0.7 | 26.0 | 30.2 | 20.91 ± 3.79 |
| pting | input-mattcl | 26.9 ± 0.9 | 25.9 | 29.6 | 20.94 ± 3.82 |
| pting | input-pting | 27.1 ± 0.9 | 25.9 | 30.1 | 21.11 ± 3.85 |
| kcen | input-pting | 47.2 ± 1.1 | 45.7 | 50.7 | 36.72 ± 6.65 |
| kcen | input-lanjian | 48.0 ± 1.2 | 46.0 | 51.5 | 37.39 ± 6.78 |
| kcen | input-mattcl | 50.2 ± 1.1 | 48.7 | 53.6 | 39.08 ± 7.07 |
| kcen | input-kcen | 50.4 ± 1.2 | 48.4 | 53.0 | 39.26 ± 7.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|