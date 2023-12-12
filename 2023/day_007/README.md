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
| mattcl | input-kcen | 1.1 ± 0.3 | 0.3 | 1.7 | 1.00 |
| lanjian | input-kcen | 1.1 ± 2.7 | 0.3 | 38.6 | 1.03 ± 2.52 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.8 | 1.04 ± 0.32 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.8 | 1.06 ± 0.31 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.6 | 1.7 | 1.08 ± 0.31 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.08 ± 0.32 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.09 ± 0.32 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.6 | 1.9 | 1.09 ± 0.31 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.8 | 1.10 ± 0.32 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.6 | 1.7 | 1.10 ± 0.31 |
| mattcl-ts | input-kcen | 14.8 ± 0.3 | 14.0 | 15.8 | 13.84 ± 3.44 |
| mattcl-ts | input-chancalan | 14.9 ± 0.4 | 13.8 | 16.2 | 13.84 ± 3.44 |
| mattcl-ts | input-mattcl | 14.9 ± 0.3 | 13.9 | 15.9 | 13.85 ± 3.44 |
| mattcl-ts | input-pting | 14.9 ± 0.3 | 13.9 | 16.1 | 13.86 ± 3.45 |
| mattcl-ts | input-lanjian | 14.9 ± 0.3 | 13.9 | 15.8 | 13.91 ± 3.46 |
| mattcl-py | input-chancalan | 16.5 ± 0.7 | 15.4 | 20.1 | 15.42 ± 3.87 |
| mattcl-py | input-mattcl | 16.5 ± 0.6 | 15.8 | 19.8 | 15.42 ± 3.86 |
| mattcl-py | input-pting | 16.6 ± 0.8 | 15.3 | 19.6 | 15.47 ± 3.90 |
| mattcl-py | input-lanjian | 16.6 ± 0.8 | 15.5 | 20.0 | 15.51 ± 3.91 |
| pting | input-mattcl | 16.9 ± 0.6 | 16.0 | 19.4 | 15.79 ± 3.94 |
| pting | input-chancalan | 17.0 ± 0.7 | 15.9 | 20.7 | 15.82 ± 3.98 |
| pting | input-lanjian | 17.0 ± 0.7 | 16.3 | 20.3 | 15.88 ± 3.98 |
| pting | input-pting | 17.1 ± 0.7 | 16.0 | 20.2 | 15.90 ± 3.99 |
| pting | input-kcen | 17.1 ± 0.6 | 16.1 | 19.5 | 15.90 ± 3.98 |
| mattcl-py | input-kcen | 17.3 ± 4.8 | 15.3 | 55.3 | 16.14 ± 5.97 |
| kcen | input-kcen | 20.2 ± 0.6 | 19.1 | 23.2 | 18.79 ± 4.69 |
| kcen | input-chancalan | 20.2 ± 0.6 | 19.3 | 23.1 | 18.87 ± 4.70 |
| kcen | input-mattcl | 20.3 ± 0.7 | 19.2 | 23.1 | 18.88 ± 4.72 |
| kcen | input-lanjian | 20.3 ± 0.8 | 19.5 | 23.4 | 18.96 ± 4.75 |
| kcen | input-pting | 20.6 ± 1.4 | 19.3 | 34.5 | 19.20 ± 4.92 |
| chancalan | input-lanjian | 24.3 ± 0.6 | 23.6 | 26.4 | 22.69 ± 5.64 |
| chancalan | input-kcen | 24.4 ± 0.8 | 23.4 | 27.7 | 22.73 ± 5.67 |
| chancalan | input-chancalan | 24.4 ± 0.8 | 23.1 | 26.9 | 22.74 ± 5.68 |
| chancalan | input-mattcl | 24.4 ± 0.8 | 23.0 | 27.7 | 22.76 ± 5.69 |
| chancalan | input-pting | 24.4 ± 0.8 | 22.9 | 27.0 | 22.78 ± 5.69 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|