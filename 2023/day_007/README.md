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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.8 | 1.05 ± 0.24 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.5 | 1.8 | 1.05 ± 0.23 |
| lanjian | input-lanjian | 1.2 ± 0.1 | 0.6 | 1.4 | 1.05 ± 0.22 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.8 | 1.05 ± 0.24 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.06 ± 0.23 |
| mattcl | input-kcen | 1.2 ± 0.1 | 0.3 | 1.7 | 1.06 ± 0.22 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.06 ± 0.23 |
| mattcl-ts | input-lanjian | 15.0 ± 0.4 | 13.9 | 15.8 | 13.10 ± 2.30 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 14.0 | 16.2 | 13.12 ± 2.30 |
| mattcl-ts | input-pting | 15.1 ± 0.4 | 14.0 | 16.1 | 13.16 ± 2.31 |
| mattcl-ts | input-kcen | 15.1 ± 0.4 | 14.2 | 16.0 | 13.18 ± 2.31 |
| mattcl-py | input-pting | 16.8 ± 0.6 | 15.6 | 19.9 | 14.64 ± 2.60 |
| mattcl-py | input-lanjian | 16.8 ± 0.7 | 16.0 | 19.9 | 14.70 ± 2.63 |
| mattcl-py | input-mattcl | 16.9 ± 0.6 | 15.5 | 20.1 | 14.73 ± 2.62 |
| mattcl-py | input-kcen | 17.1 ± 3.8 | 16.0 | 65.8 | 14.95 ± 4.21 |
| pting | input-kcen | 17.3 ± 0.6 | 16.5 | 20.1 | 15.12 ± 2.68 |
| pting | input-pting | 17.3 ± 0.6 | 16.4 | 20.0 | 15.12 ± 2.69 |
| pting | input-lanjian | 17.3 ± 0.7 | 16.2 | 20.0 | 15.14 ± 2.69 |
| pting | input-mattcl | 17.3 ± 0.8 | 15.8 | 21.1 | 15.14 ± 2.72 |
| kcen | input-lanjian | 20.5 ± 0.8 | 19.2 | 24.2 | 17.94 ± 3.20 |
| kcen | input-pting | 20.7 ± 0.8 | 19.2 | 23.6 | 18.03 ± 3.22 |
| kcen | input-mattcl | 20.8 ± 0.7 | 19.8 | 23.3 | 18.20 ± 3.23 |
| kcen | input-kcen | 21.1 ± 3.7 | 19.5 | 57.2 | 18.40 ± 4.53 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|