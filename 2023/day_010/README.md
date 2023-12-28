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
| mattcl | input-mattcl | 1.0 ± 0.4 | 0.4 | 4.4 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.4 | 0.5 | 4.3 | 1.12 ± 0.64 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.6 | 1.7 | 1.35 ± 0.62 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.9 | 1.8 | 1.42 ± 0.64 |
| lanjian | input-lanjian | 3.0 ± 0.4 | 2.3 | 5.0 | 2.92 ± 1.33 |
| lanjian | input-mattcl | 3.0 ± 0.4 | 2.2 | 5.4 | 2.94 ± 1.34 |
| lanjian | input-kcen | 3.2 ± 0.3 | 2.5 | 5.3 | 3.10 ± 1.36 |
| lanjian | input-pting | 3.2 ± 0.2 | 2.5 | 3.9 | 3.14 ± 1.37 |
| mattcl-ts | input-pting | 17.7 ± 0.5 | 16.1 | 19.5 | 17.35 ± 7.48 |
| mattcl-ts | input-mattcl | 17.8 ± 0.4 | 16.7 | 19.5 | 17.47 ± 7.52 |
| mattcl-ts | input-kcen | 18.2 ± 0.5 | 17.0 | 20.0 | 17.82 ± 7.68 |
| mattcl-ts | input-lanjian | 18.3 ± 1.0 | 16.6 | 21.8 | 17.97 ± 7.79 |
| mattcl-py | input-pting | 27.3 ± 0.5 | 26.1 | 29.1 | 26.73 ± 11.50 |
| pting | input-pting | 27.7 ± 0.9 | 25.9 | 31.4 | 27.11 ± 11.69 |
| mattcl-py | input-kcen | 28.4 ± 4.8 | 24.7 | 42.9 | 27.84 ± 12.85 |
| mattcl-py | input-lanjian | 28.5 ± 2.3 | 26.0 | 38.7 | 27.97 ± 12.23 |
| pting | input-mattcl | 28.8 ± 0.6 | 27.4 | 30.3 | 28.17 ± 12.13 |
| pting | input-kcen | 29.4 ± 0.7 | 28.6 | 32.0 | 28.82 ± 12.41 |
| pting | input-lanjian | 29.6 ± 1.6 | 27.3 | 37.7 | 28.98 ± 12.57 |
| mattcl-py | input-mattcl | 33.7 ± 10.3 | 25.9 | 60.7 | 33.00 ± 17.39 |
| kcen | input-pting | 49.3 ± 0.8 | 47.4 | 50.9 | 48.27 ± 20.77 |
| kcen | input-kcen | 51.2 ± 1.1 | 49.4 | 54.1 | 50.14 ± 21.59 |
| kcen | input-mattcl | 55.3 ± 3.5 | 51.9 | 65.4 | 54.18 ± 23.54 |
| kcen | input-lanjian | 55.6 ± 10.4 | 48.6 | 88.4 | 54.48 ± 25.53 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|