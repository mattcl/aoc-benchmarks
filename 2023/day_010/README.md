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
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 2.0 | 1.01 ± 0.19 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 1.8 | 1.01 ± 0.20 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.6 | 2.1 | 1.03 ± 0.22 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.3 | 4.8 | 2.38 ± 0.38 |
| lanjian | input-pting | 3.1 ± 0.2 | 2.5 | 3.9 | 2.41 ± 0.37 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.7 | 5.7 | 2.41 ± 0.41 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.5 | 5.8 | 2.41 ± 0.40 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.8 | 18.5 | 13.46 ± 1.92 |
| mattcl-ts | input-mattcl | 17.6 ± 0.4 | 16.3 | 18.8 | 13.47 ± 1.93 |
| mattcl-ts | input-lanjian | 17.7 ± 0.4 | 16.7 | 18.7 | 13.54 ± 1.93 |
| mattcl-ts | input-kcen | 17.8 ± 2.5 | 16.6 | 48.8 | 13.65 ± 2.70 |
| mattcl-py | input-kcen | 26.0 ± 1.0 | 24.7 | 29.5 | 19.85 ± 2.90 |
| mattcl-py | input-mattcl | 26.0 ± 0.9 | 24.8 | 29.5 | 19.88 ± 2.88 |
| mattcl-py | input-lanjian | 26.4 ± 0.9 | 25.1 | 29.8 | 20.20 ± 2.93 |
| mattcl-py | input-pting | 26.9 ± 4.4 | 25.0 | 72.1 | 20.60 ± 4.44 |
| pting | input-kcen | 27.0 ± 0.7 | 25.9 | 29.6 | 20.61 ± 2.96 |
| pting | input-lanjian | 27.2 ± 0.5 | 26.4 | 29.3 | 20.83 ± 2.97 |
| pting | input-mattcl | 27.3 ± 0.7 | 26.3 | 31.2 | 20.84 ± 2.99 |
| pting | input-pting | 27.4 ± 0.8 | 26.4 | 29.8 | 20.99 ± 3.02 |
| kcen | input-pting | 47.4 ± 1.3 | 45.3 | 50.8 | 36.27 ± 5.21 |
| kcen | input-lanjian | 48.3 ± 1.2 | 46.6 | 51.6 | 36.97 ± 5.30 |
| kcen | input-kcen | 50.5 ± 1.3 | 48.0 | 53.8 | 38.59 ± 5.54 |
| kcen | input-mattcl | 50.6 ± 1.3 | 48.2 | 53.4 | 38.67 ± 5.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|