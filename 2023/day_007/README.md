# Day 7 benchmarks

[link to problem](https://adventofcode.com/2023/day/7)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 7)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-kcen | 1.0 ± 0.3 | 0.3 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.8 | 1.04 ± 0.37 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.6 | 1.5 | 1.11 ± 0.37 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.6 | 1.5 | 1.11 ± 0.36 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.6 | 1.12 ± 0.35 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.9 | 1.13 ± 0.38 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.15 ± 0.37 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.8 | 1.15 ± 0.36 |
| mattcl-ts | input-lanjian | 13.9 ± 0.3 | 13.1 | 14.7 | 13.68 ± 3.89 |
| mattcl-ts | input-kcen | 14.0 ± 0.3 | 13.2 | 14.8 | 13.74 ± 3.91 |
| mattcl-ts | input-mattcl | 14.1 ± 0.4 | 13.2 | 16.4 | 13.81 ± 3.93 |
| mattcl-ts | input-pting | 14.3 ± 4.0 | 13.1 | 70.7 | 14.02 ± 5.60 |
| mattcl-py | input-mattcl | 16.4 ± 0.6 | 15.6 | 19.9 | 16.15 ± 4.62 |
| mattcl-py | input-lanjian | 16.5 ± 0.7 | 15.2 | 19.3 | 16.18 ± 4.64 |
| mattcl-py | input-kcen | 16.6 ± 2.2 | 15.3 | 45.2 | 16.32 ± 5.11 |
| mattcl-py | input-pting | 16.7 ± 1.8 | 15.4 | 36.0 | 16.39 ± 4.99 |
| pting | input-mattcl | 16.8 ± 0.5 | 15.9 | 19.0 | 16.50 ± 4.70 |
| pting | input-lanjian | 16.8 ± 0.7 | 15.7 | 20.9 | 16.52 ± 4.73 |
| pting | input-kcen | 16.9 ± 0.7 | 16.1 | 19.7 | 16.64 ± 4.76 |
| pting | input-pting | 17.0 ± 0.7 | 16.1 | 20.1 | 16.66 ± 4.77 |
| kcen | input-mattcl | 20.1 ± 0.6 | 19.1 | 22.8 | 19.78 ± 5.64 |
| kcen | input-kcen | 20.2 ± 0.7 | 18.9 | 23.1 | 19.84 ± 5.67 |
| kcen | input-lanjian | 20.2 ± 0.7 | 18.9 | 23.1 | 19.84 ± 5.67 |
| kcen | input-pting | 20.2 ± 0.8 | 19.4 | 23.3 | 19.88 ± 5.68 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|