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
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.4 | 2.0 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.6 | 1.8 | 1.00 ± 0.23 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.6 | 1.7 | 1.01 ± 0.23 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.8 | 2.0 | 1.03 ± 0.23 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.2 | 5.6 | 2.33 ± 0.45 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.2 | 4.7 | 2.33 ± 0.44 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.2 | 4.4 | 2.34 ± 0.44 |
| lanjian | input-lanjian | 3.1 ± 0.4 | 2.4 | 6.1 | 2.39 ± 0.51 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.4 | 18.9 | 13.45 ± 2.40 |
| mattcl-ts | input-pting | 17.5 ± 0.4 | 16.7 | 18.6 | 13.50 ± 2.41 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.2 | 18.7 | 13.54 ± 2.42 |
| mattcl-ts | input-lanjian | 17.8 ± 0.4 | 16.7 | 19.4 | 13.67 ± 2.44 |
| mattcl-py | input-mattcl | 26.0 ± 0.8 | 24.8 | 29.2 | 20.05 ± 3.60 |
| mattcl-py | input-kcen | 26.1 ± 1.1 | 24.8 | 31.4 | 20.11 ± 3.65 |
| mattcl-py | input-pting | 26.4 ± 1.0 | 24.9 | 29.9 | 20.32 ± 3.68 |
| pting | input-pting | 27.2 ± 0.6 | 26.0 | 29.6 | 20.91 ± 3.74 |
| pting | input-kcen | 27.2 ± 0.9 | 25.8 | 30.1 | 20.93 ± 3.77 |
| pting | input-mattcl | 27.2 ± 0.8 | 26.0 | 30.3 | 20.96 ± 3.76 |
| pting | input-lanjian | 27.2 ± 0.9 | 26.0 | 30.3 | 20.96 ± 3.78 |
| mattcl-py | input-lanjian | 27.4 ± 6.0 | 24.5 | 72.0 | 21.10 ± 5.96 |
| kcen | input-pting | 47.7 ± 1.4 | 45.2 | 52.9 | 36.73 ± 6.59 |
| kcen | input-lanjian | 48.6 ± 2.2 | 46.3 | 62.8 | 37.44 ± 6.84 |
| kcen | input-mattcl | 50.5 ± 1.2 | 48.3 | 53.1 | 38.87 ± 6.94 |
| kcen | input-kcen | 50.7 ± 1.3 | 48.5 | 53.7 | 39.02 ± 6.99 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|