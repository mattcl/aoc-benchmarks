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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.8 | 1.00 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.7 | 1.7 | 1.02 ± 0.23 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.7 | 2.0 | 1.04 ± 0.25 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 2.0 | 1.06 ± 0.26 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.2 | 4.7 | 2.46 ± 0.47 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.2 | 5.7 | 2.48 ± 0.48 |
| lanjian | input-lanjian | 3.0 ± 0.3 | 2.3 | 5.7 | 2.49 ± 0.51 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.2 | 5.8 | 2.49 ± 0.49 |
| mattcl-ts | input-mattcl | 16.8 ± 0.4 | 15.8 | 17.9 | 13.77 ± 2.48 |
| mattcl-ts | input-kcen | 16.8 ± 0.4 | 16.1 | 17.9 | 13.81 ± 2.48 |
| mattcl-ts | input-pting | 16.9 ± 0.4 | 16.0 | 17.8 | 13.83 ± 2.48 |
| mattcl-ts | input-lanjian | 17.0 ± 0.4 | 15.8 | 18.0 | 13.91 ± 2.50 |
| mattcl-py | input-kcen | 25.4 ± 0.9 | 24.3 | 29.6 | 20.87 ± 3.79 |
| mattcl-py | input-mattcl | 25.8 ± 0.9 | 24.7 | 28.9 | 21.16 ± 3.84 |
| mattcl-py | input-pting | 25.9 ± 0.8 | 25.0 | 29.1 | 21.27 ± 3.85 |
| mattcl-py | input-lanjian | 25.9 ± 0.8 | 24.6 | 29.7 | 21.27 ± 3.84 |
| pting | input-kcen | 26.6 ± 1.0 | 25.1 | 29.7 | 21.84 ± 3.98 |
| pting | input-mattcl | 26.7 ± 0.8 | 25.7 | 29.5 | 21.87 ± 3.94 |
| pting | input-pting | 26.8 ± 0.8 | 25.6 | 29.6 | 22.01 ± 3.97 |
| pting | input-lanjian | 26.9 ± 0.8 | 25.8 | 29.7 | 22.03 ± 3.98 |
| kcen | input-pting | 47.0 ± 1.0 | 45.1 | 49.8 | 38.56 ± 6.91 |
| kcen | input-lanjian | 47.6 ± 1.0 | 46.2 | 50.8 | 39.04 ± 7.00 |
| kcen | input-mattcl | 49.8 ± 0.9 | 48.3 | 51.9 | 40.82 ± 7.30 |
| kcen | input-kcen | 49.9 ± 1.7 | 47.5 | 59.5 | 40.95 ± 7.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|