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
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.4 | 1.00 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.2 | 1.6 | 1.06 ± 0.30 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.07 ± 0.29 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.4 | 1.7 | 1.07 ± 0.30 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.6 | 1.8 | 1.08 ± 0.29 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.09 ± 0.30 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.4 | 1.09 ± 0.29 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.5 | 1.7 | 1.10 ± 0.30 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.6 | 1.10 ± 0.30 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.6 | 1.11 ± 0.30 |
| mattcl-ts | input-lanjian | 14.8 ± 0.4 | 13.9 | 15.9 | 14.11 ± 3.19 |
| mattcl-ts | input-chancalan | 14.9 ± 0.4 | 13.7 | 15.7 | 14.16 ± 3.20 |
| mattcl-ts | input-kcen | 14.9 ± 0.3 | 14.1 | 16.1 | 14.16 ± 3.20 |
| mattcl-ts | input-pting | 14.9 ± 0.4 | 14.0 | 16.2 | 14.19 ± 3.21 |
| mattcl-ts | input-mattcl | 15.1 ± 2.7 | 14.0 | 42.1 | 14.39 ± 4.11 |
| mattcl-py | input-chancalan | 16.5 ± 0.5 | 15.6 | 18.8 | 15.66 ± 3.55 |
| mattcl-py | input-pting | 16.5 ± 0.6 | 15.7 | 20.1 | 15.67 ± 3.57 |
| mattcl-py | input-kcen | 16.5 ± 0.5 | 15.3 | 18.3 | 15.67 ± 3.55 |
| mattcl-py | input-mattcl | 16.6 ± 0.7 | 15.9 | 19.5 | 15.81 ± 3.62 |
| mattcl-py | input-lanjian | 16.6 ± 0.7 | 15.6 | 19.8 | 15.82 ± 3.63 |
| pting | input-pting | 17.0 ± 0.6 | 15.9 | 20.7 | 16.17 ± 3.68 |
| pting | input-lanjian | 17.0 ± 0.6 | 16.2 | 19.9 | 16.20 ± 3.69 |
| pting | input-chancalan | 17.0 ± 0.7 | 16.0 | 19.8 | 16.21 ± 3.70 |
| pting | input-kcen | 17.1 ± 0.7 | 16.1 | 20.4 | 16.26 ± 3.71 |
| pting | input-mattcl | 17.3 ± 2.5 | 16.2 | 48.3 | 16.43 ± 4.37 |
| kcen | input-kcen | 20.3 ± 0.7 | 19.4 | 23.1 | 19.33 ± 4.39 |
| kcen | input-lanjian | 20.4 ± 0.7 | 19.5 | 23.9 | 19.41 ± 4.41 |
| kcen | input-chancalan | 20.4 ± 0.7 | 19.6 | 23.3 | 19.41 ± 4.41 |
| kcen | input-mattcl | 20.4 ± 0.8 | 19.2 | 23.5 | 19.43 ± 4.43 |
| kcen | input-pting | 20.6 ± 3.3 | 19.2 | 57.8 | 19.62 ± 5.41 |
| chancalan | input-kcen | 24.4 ± 0.7 | 23.2 | 27.5 | 23.20 ± 5.26 |
| chancalan | input-pting | 24.5 ± 0.5 | 23.5 | 26.3 | 23.28 ± 5.25 |
| chancalan | input-chancalan | 24.5 ± 0.8 | 23.4 | 27.6 | 23.31 ± 5.30 |
| chancalan | input-mattcl | 24.5 ± 0.8 | 23.2 | 27.3 | 23.34 ± 5.30 |
| chancalan | input-lanjian | 24.7 ± 0.9 | 23.3 | 27.2 | 23.48 ± 5.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|