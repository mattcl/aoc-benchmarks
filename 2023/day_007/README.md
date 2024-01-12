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
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.8 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.28 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.7 | 1.05 ± 0.27 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.05 ± 0.26 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.05 ± 0.26 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 2.0 | 1.06 ± 0.27 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.3 | 2.0 | 1.06 ± 0.29 |
| lanjian | input-kcen | 1.2 ± 0.1 | 0.7 | 1.7 | 1.07 ± 0.25 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.9 | 1.07 ± 0.28 |
| lanjian | input-pting | 1.3 ± 3.0 | 0.3 | 42.7 | 1.14 ± 2.58 |
| mattcl-ts | input-kcen | 14.9 ± 0.4 | 13.7 | 16.0 | 12.99 ± 2.68 |
| mattcl-ts | input-lanjian | 15.0 ± 0.4 | 14.1 | 16.0 | 13.02 ± 2.69 |
| mattcl-ts | input-chancalan | 15.0 ± 0.4 | 14.0 | 15.9 | 13.04 ± 2.69 |
| mattcl-ts | input-pting | 15.0 ± 0.4 | 14.1 | 16.3 | 13.04 ± 2.69 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 14.0 | 16.3 | 13.07 ± 2.70 |
| mattcl-py | input-chancalan | 16.7 ± 0.6 | 15.4 | 19.4 | 14.51 ± 3.02 |
| mattcl-py | input-kcen | 16.7 ± 0.6 | 15.9 | 19.7 | 14.56 ± 3.03 |
| mattcl-py | input-pting | 16.8 ± 0.7 | 15.4 | 19.3 | 14.61 ± 3.05 |
| mattcl-py | input-mattcl | 16.9 ± 0.8 | 15.8 | 20.3 | 14.65 ± 3.08 |
| mattcl-py | input-lanjian | 16.9 ± 0.7 | 15.7 | 19.3 | 14.66 ± 3.06 |
| pting | input-mattcl | 17.3 ± 0.6 | 16.4 | 20.1 | 15.04 ± 3.13 |
| pting | input-chancalan | 17.3 ± 0.7 | 16.4 | 20.4 | 15.08 ± 3.15 |
| pting | input-pting | 17.4 ± 0.7 | 16.3 | 20.6 | 15.11 ± 3.15 |
| pting | input-kcen | 17.4 ± 0.7 | 16.5 | 20.2 | 15.14 ± 3.17 |
| pting | input-lanjian | 17.6 ± 3.0 | 16.1 | 56.3 | 15.30 ± 4.10 |
| kcen | input-lanjian | 20.6 ± 0.6 | 19.6 | 23.3 | 17.92 ± 3.71 |
| kcen | input-chancalan | 20.6 ± 0.7 | 19.0 | 23.0 | 17.94 ± 3.72 |
| kcen | input-kcen | 20.7 ± 0.7 | 19.6 | 23.2 | 17.98 ± 3.74 |
| kcen | input-mattcl | 20.7 ± 0.7 | 19.5 | 23.5 | 18.04 ± 3.75 |
| kcen | input-pting | 20.8 ± 0.8 | 19.6 | 24.0 | 18.10 ± 3.78 |
| chancalan | input-kcen | 24.6 ± 0.9 | 23.1 | 28.4 | 21.40 ± 4.46 |
| chancalan | input-pting | 24.6 ± 0.7 | 23.6 | 27.6 | 21.40 ± 4.43 |
| chancalan | input-lanjian | 24.7 ± 0.7 | 23.6 | 27.4 | 21.44 ± 4.44 |
| chancalan | input-chancalan | 24.7 ± 0.8 | 23.7 | 28.4 | 21.49 ± 4.46 |
| chancalan | input-mattcl | 24.7 ± 0.7 | 23.5 | 26.7 | 21.52 ± 4.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|