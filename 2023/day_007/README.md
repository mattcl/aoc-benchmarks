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

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.2 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.2 | 1.7 | 1.00 ± 0.25 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.24 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.25 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.03 ± 0.23 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.6 | 1.03 ± 0.23 |
| mattcl | input-chancalan | 1.2 ± 0.1 | 0.7 | 1.6 | 1.04 ± 0.22 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.04 ± 0.24 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.9 | 1.07 ± 0.25 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.7 | 2.0 | 1.09 ± 0.24 |
| mattcl-ts | input-chancalan | 14.9 ± 0.3 | 13.9 | 15.9 | 13.09 ± 2.26 |
| mattcl-ts | input-lanjian | 14.9 ± 0.4 | 14.0 | 15.8 | 13.10 ± 2.27 |
| mattcl-ts | input-mattcl | 14.9 ± 0.4 | 13.9 | 16.0 | 13.12 ± 2.27 |
| mattcl-ts | input-kcen | 15.0 ± 0.4 | 13.9 | 16.4 | 13.17 ± 2.28 |
| mattcl-ts | input-pting | 15.0 ± 0.4 | 14.0 | 17.9 | 13.18 ± 2.29 |
| mattcl-py | input-pting | 16.7 ± 0.7 | 15.5 | 20.4 | 14.65 ± 2.58 |
| mattcl-py | input-kcen | 16.7 ± 0.6 | 15.9 | 19.7 | 14.66 ± 2.57 |
| mattcl-py | input-chancalan | 16.7 ± 0.7 | 15.4 | 19.7 | 14.71 ± 2.59 |
| mattcl-py | input-mattcl | 16.8 ± 0.7 | 15.8 | 19.8 | 14.75 ± 2.60 |
| mattcl-py | input-lanjian | 16.8 ± 0.8 | 15.9 | 19.8 | 14.79 ± 2.62 |
| pting | input-pting | 17.1 ± 0.6 | 16.0 | 20.0 | 15.03 ± 2.62 |
| pting | input-lanjian | 17.2 ± 0.7 | 16.0 | 20.4 | 15.14 ± 2.65 |
| pting | input-kcen | 17.3 ± 0.7 | 15.9 | 20.4 | 15.18 ± 2.67 |
| pting | input-chancalan | 17.3 ± 0.7 | 16.0 | 20.6 | 15.21 ± 2.68 |
| pting | input-mattcl | 17.3 ± 0.7 | 16.1 | 20.6 | 15.22 ± 2.67 |
| kcen | input-chancalan | 20.4 ± 0.6 | 19.2 | 23.0 | 17.89 ± 3.10 |
| kcen | input-pting | 20.4 ± 0.6 | 18.9 | 22.5 | 17.96 ± 3.12 |
| kcen | input-kcen | 20.5 ± 0.7 | 19.6 | 24.1 | 18.05 ± 3.15 |
| kcen | input-mattcl | 20.6 ± 0.6 | 19.8 | 23.0 | 18.09 ± 3.14 |
| kcen | input-lanjian | 20.6 ± 0.7 | 19.7 | 23.5 | 18.14 ± 3.17 |
| chancalan | input-kcen | 24.5 ± 0.7 | 23.2 | 27.9 | 21.52 ± 3.73 |
| chancalan | input-chancalan | 24.5 ± 0.5 | 23.5 | 27.1 | 21.53 ± 3.71 |
| chancalan | input-mattcl | 24.7 ± 0.8 | 23.5 | 27.9 | 21.66 ± 3.76 |
| chancalan | input-lanjian | 24.7 ± 1.0 | 23.3 | 28.0 | 21.67 ± 3.81 |
| chancalan | input-pting | 24.7 ± 0.7 | 23.5 | 27.6 | 21.72 ± 3.77 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|