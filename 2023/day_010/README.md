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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.6 | 1.00 ± 0.20 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.5 | 1.9 | 1.02 ± 0.22 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.7 | 2.1 | 1.07 ± 0.23 |
| lanjian | input-pting | 3.1 ± 0.2 | 2.3 | 4.9 | 2.36 ± 0.39 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.2 | 6.0 | 2.39 ± 0.46 |
| lanjian | input-kcen | 3.1 ± 0.4 | 2.3 | 6.0 | 2.39 ± 0.44 |
| lanjian | input-lanjian | 3.2 ± 0.3 | 2.4 | 6.2 | 2.41 ± 0.43 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.4 | 18.9 | 13.33 ± 1.99 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.8 | 18.7 | 13.39 ± 2.00 |
| mattcl-ts | input-lanjian | 17.7 ± 0.5 | 16.8 | 19.0 | 13.48 ± 2.02 |
| mattcl-ts | input-kcen | 17.8 ± 2.8 | 16.8 | 53.5 | 13.52 ± 2.91 |
| mattcl-py | input-kcen | 25.8 ± 0.8 | 24.6 | 29.1 | 19.62 ± 2.96 |
| mattcl-py | input-mattcl | 26.2 ± 1.0 | 24.7 | 29.7 | 19.89 ± 3.03 |
| mattcl-py | input-pting | 26.3 ± 0.9 | 24.8 | 30.0 | 19.95 ± 3.02 |
| mattcl-py | input-lanjian | 26.4 ± 1.0 | 25.0 | 31.2 | 20.03 ± 3.05 |
| pting | input-kcen | 27.1 ± 0.9 | 25.8 | 32.4 | 20.60 ± 3.12 |
| pting | input-mattcl | 27.2 ± 0.8 | 26.2 | 29.9 | 20.68 ± 3.11 |
| pting | input-lanjian | 27.3 ± 0.6 | 26.3 | 30.0 | 20.76 ± 3.10 |
| pting | input-pting | 27.4 ± 0.8 | 25.7 | 30.2 | 20.83 ± 3.13 |
| kcen | input-pting | 47.5 ± 0.9 | 45.8 | 50.1 | 36.07 ± 5.37 |
| kcen | input-lanjian | 48.6 ± 1.6 | 46.5 | 55.5 | 36.91 ± 5.58 |
| kcen | input-mattcl | 50.3 ± 1.1 | 48.2 | 53.9 | 38.21 ± 5.70 |
| kcen | input-kcen | 50.6 ± 1.2 | 48.5 | 54.4 | 38.47 ± 5.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|