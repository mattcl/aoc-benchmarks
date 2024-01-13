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
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.28 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.7 | 1.03 ± 0.26 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.26 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.8 | 1.03 ± 0.27 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 2.0 | 1.04 ± 0.28 |
| mattcl | input-mattcl | 1.2 ± 0.1 | 0.6 | 1.7 | 1.04 ± 0.24 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.7 | 1.05 ± 0.27 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.3 | 2.0 | 1.06 ± 0.27 |
| mattcl | input-lanjian | 1.2 ± 0.1 | 0.5 | 1.7 | 1.07 ± 0.25 |
| mattcl-ts | input-chancalan | 14.8 ± 0.3 | 13.9 | 15.8 | 13.12 ± 2.71 |
| mattcl-ts | input-mattcl | 14.8 ± 0.4 | 13.8 | 16.1 | 13.14 ± 2.72 |
| mattcl-ts | input-lanjian | 14.8 ± 0.3 | 14.1 | 15.7 | 13.15 ± 2.72 |
| mattcl-ts | input-kcen | 14.8 ± 0.4 | 13.9 | 16.0 | 13.16 ± 2.73 |
| mattcl-ts | input-pting | 14.9 ± 0.4 | 13.8 | 16.5 | 13.16 ± 2.73 |
| mattcl-py | input-chancalan | 16.4 ± 0.7 | 15.5 | 19.7 | 14.57 ± 3.05 |
| mattcl-py | input-pting | 16.5 ± 0.6 | 15.5 | 20.1 | 14.60 ± 3.04 |
| mattcl-py | input-kcen | 16.5 ± 0.7 | 15.5 | 19.5 | 14.63 ± 3.07 |
| mattcl-py | input-lanjian | 16.5 ± 0.6 | 15.4 | 19.9 | 14.63 ± 3.06 |
| mattcl-py | input-mattcl | 16.5 ± 0.7 | 15.5 | 19.6 | 14.66 ± 3.09 |
| pting | input-chancalan | 17.1 ± 0.6 | 16.3 | 20.6 | 15.18 ± 3.17 |
| pting | input-pting | 17.2 ± 0.6 | 16.2 | 20.0 | 15.20 ± 3.17 |
| pting | input-kcen | 17.2 ± 0.6 | 16.5 | 19.5 | 15.23 ± 3.17 |
| pting | input-mattcl | 17.2 ± 0.7 | 16.3 | 20.5 | 15.27 ± 3.20 |
| pting | input-lanjian | 17.3 ± 0.8 | 16.1 | 20.6 | 15.30 ± 3.23 |
| kcen | input-kcen | 20.2 ± 0.6 | 19.3 | 22.8 | 17.88 ± 3.71 |
| kcen | input-lanjian | 20.3 ± 0.6 | 19.5 | 22.6 | 17.96 ± 3.73 |
| kcen | input-chancalan | 20.3 ± 0.9 | 19.0 | 24.0 | 18.03 ± 3.78 |
| kcen | input-pting | 20.4 ± 0.7 | 19.2 | 23.4 | 18.05 ± 3.76 |
| kcen | input-mattcl | 20.4 ± 0.9 | 19.4 | 24.0 | 18.06 ± 3.79 |
| chancalan | input-kcen | 24.3 ± 0.7 | 23.3 | 27.0 | 21.53 ± 4.47 |
| chancalan | input-pting | 24.4 ± 0.7 | 23.1 | 27.3 | 21.60 ± 4.49 |
| chancalan | input-chancalan | 24.4 ± 0.8 | 23.2 | 26.8 | 21.65 ± 4.51 |
| chancalan | input-mattcl | 24.5 ± 0.8 | 23.2 | 27.5 | 21.71 ± 4.52 |
| chancalan | input-lanjian | 24.7 ± 2.2 | 23.4 | 47.7 | 21.93 ± 4.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|