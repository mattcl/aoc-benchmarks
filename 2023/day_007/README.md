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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.7 | 1.7 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.8 | 1.00 ± 0.20 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 ± 0.21 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.8 | 1.00 ± 0.22 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.6 | 1.7 | 1.01 ± 0.19 |
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.19 |
| lanjian | input-chancalan | 1.3 ± 0.1 | 0.7 | 1.7 | 1.01 ± 0.19 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.6 | 1.7 | 1.01 ± 0.21 |
| lanjian | input-kcen | 1.3 ± 0.1 | 0.7 | 1.7 | 1.02 ± 0.18 |
| lanjian | input-lanjian | 1.3 ± 0.1 | 0.7 | 1.8 | 1.02 ± 0.18 |
| mattcl-ts | input-lanjian | 15.0 ± 0.4 | 14.2 | 16.0 | 12.12 ± 1.74 |
| mattcl-ts | input-chancalan | 15.1 ± 0.4 | 14.1 | 16.0 | 12.13 ± 1.74 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.3 | 15.9 | 12.13 ± 1.74 |
| mattcl-ts | input-mattcl | 15.1 ± 0.4 | 14.3 | 16.1 | 12.13 ± 1.74 |
| mattcl-ts | input-kcen | 15.1 ± 0.3 | 14.3 | 16.2 | 12.15 ± 1.74 |
| mattcl-py | input-pting | 16.7 ± 0.6 | 15.5 | 19.8 | 13.44 ± 1.96 |
| mattcl-py | input-lanjian | 16.7 ± 0.6 | 15.4 | 19.8 | 13.48 ± 1.97 |
| mattcl-py | input-kcen | 16.8 ± 0.6 | 16.0 | 19.7 | 13.50 ± 1.97 |
| mattcl-py | input-mattcl | 16.8 ± 0.8 | 15.5 | 19.9 | 13.54 ± 2.01 |
| mattcl-py | input-chancalan | 16.8 ± 0.7 | 15.7 | 19.7 | 13.56 ± 2.00 |
| pting | input-kcen | 17.2 ± 0.6 | 15.7 | 20.7 | 13.84 ± 2.02 |
| pting | input-mattcl | 17.3 ± 0.6 | 15.9 | 20.7 | 13.90 ± 2.03 |
| pting | input-pting | 17.3 ± 0.7 | 16.4 | 20.3 | 13.91 ± 2.05 |
| pting | input-lanjian | 17.3 ± 1.1 | 15.9 | 28.8 | 13.94 ± 2.15 |
| pting | input-chancalan | 17.3 ± 0.7 | 16.3 | 20.6 | 13.96 ± 2.06 |
| kcen | input-lanjian | 20.5 ± 0.6 | 19.0 | 23.8 | 16.48 ± 2.39 |
| kcen | input-kcen | 20.6 ± 0.6 | 19.6 | 23.5 | 16.57 ± 2.40 |
| kcen | input-mattcl | 20.6 ± 0.8 | 19.2 | 24.0 | 16.58 ± 2.43 |
| kcen | input-chancalan | 20.7 ± 0.8 | 19.1 | 23.5 | 16.66 ± 2.44 |
| kcen | input-pting | 20.7 ± 1.9 | 19.2 | 41.8 | 16.71 ± 2.83 |
| chancalan | input-pting | 24.5 ± 0.6 | 23.4 | 27.6 | 19.72 ± 2.84 |
| chancalan | input-mattcl | 24.7 ± 0.9 | 23.5 | 27.6 | 19.90 ± 2.90 |
| chancalan | input-kcen | 24.7 ± 0.7 | 23.5 | 27.3 | 19.92 ± 2.88 |
| chancalan | input-chancalan | 24.7 ± 0.7 | 23.5 | 28.4 | 19.93 ± 2.88 |
| chancalan | input-lanjian | 24.8 ± 0.9 | 23.3 | 27.6 | 19.98 ± 2.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|