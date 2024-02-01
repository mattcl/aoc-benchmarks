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
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.9 | 2.1 | 1.00 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.9 | 1.8 | 1.00 ± 0.19 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 0.8 | 2.3 | 1.05 ± 0.19 |
| mattcl | input-kcen | 1.5 ± 0.2 | 1.1 | 2.0 | 1.06 ± 0.19 |
| lanjian | input-mattcl | 3.2 ± 0.1 | 2.5 | 3.9 | 2.19 ± 0.31 |
| lanjian | input-pting | 3.2 ± 0.3 | 2.4 | 5.7 | 2.19 ± 0.34 |
| lanjian | input-kcen | 3.2 ± 0.2 | 2.5 | 4.9 | 2.20 ± 0.32 |
| lanjian | input-lanjian | 3.2 ± 0.2 | 2.6 | 4.7 | 2.20 ± 0.32 |
| mattcl-ts | input-pting | 17.0 ± 0.5 | 16.0 | 18.8 | 11.77 ± 1.61 |
| mattcl-ts | input-mattcl | 17.1 ± 0.4 | 16.0 | 18.6 | 11.79 ± 1.61 |
| mattcl-ts | input-kcen | 17.1 ± 0.4 | 16.0 | 18.4 | 11.83 ± 1.60 |
| mattcl-ts | input-lanjian | 17.3 ± 0.5 | 15.9 | 18.8 | 11.93 ± 1.63 |
| mattcl-py | input-kcen | 25.7 ± 0.9 | 24.5 | 29.4 | 17.73 ± 2.44 |
| mattcl-py | input-mattcl | 26.0 ± 1.0 | 24.8 | 30.2 | 17.95 ± 2.50 |
| mattcl-py | input-lanjian | 26.3 ± 0.7 | 25.1 | 29.9 | 18.20 ± 2.49 |
| mattcl-py | input-pting | 26.4 ± 1.1 | 25.1 | 32.0 | 18.23 ± 2.54 |
| pting | input-kcen | 27.0 ± 0.7 | 25.8 | 29.8 | 18.63 ± 2.54 |
| pting | input-mattcl | 27.1 ± 0.7 | 25.8 | 29.8 | 18.71 ± 2.55 |
| pting | input-lanjian | 27.3 ± 0.7 | 26.1 | 30.2 | 18.84 ± 2.57 |
| pting | input-pting | 27.4 ± 0.9 | 26.2 | 30.2 | 18.92 ± 2.61 |
| kcen | input-pting | 48.1 ± 4.3 | 46.2 | 80.4 | 33.24 ± 5.35 |
| kcen | input-lanjian | 48.5 ± 1.1 | 46.7 | 51.4 | 33.49 ± 4.54 |
| kcen | input-mattcl | 50.7 ± 1.3 | 48.6 | 54.9 | 35.02 ± 4.77 |
| kcen | input-kcen | 50.8 ± 1.2 | 48.8 | 53.8 | 35.08 ± 4.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|