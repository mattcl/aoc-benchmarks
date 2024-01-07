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
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.00 ± 0.21 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.4 | 1.00 ± 0.22 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.22 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.6 | 1.7 | 1.02 ± 0.21 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.8 | 1.02 ± 0.21 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.21 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 1.8 | 1.02 ± 0.23 |
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.4 | 1.8 | 1.02 ± 0.21 |
| lanjian | input-mattcl | 1.3 ± 0.1 | 0.5 | 1.8 | 1.03 ± 0.20 |
| mattcl-ts | input-chancalan | 14.8 ± 0.4 | 13.9 | 15.9 | 12.10 ± 1.91 |
| mattcl-ts | input-pting | 14.8 ± 0.4 | 14.0 | 15.8 | 12.13 ± 1.91 |
| mattcl-ts | input-mattcl | 14.9 ± 0.3 | 14.0 | 15.8 | 12.14 ± 1.91 |
| mattcl-ts | input-lanjian | 14.9 ± 0.4 | 13.9 | 15.8 | 12.15 ± 1.92 |
| mattcl-ts | input-kcen | 14.9 ± 0.3 | 13.8 | 15.9 | 12.15 ± 1.91 |
| mattcl-py | input-chancalan | 16.4 ± 0.6 | 15.5 | 19.4 | 13.42 ± 2.14 |
| mattcl-py | input-mattcl | 16.5 ± 0.7 | 15.3 | 19.1 | 13.47 ± 2.17 |
| mattcl-py | input-kcen | 16.5 ± 0.6 | 15.5 | 19.6 | 13.47 ± 2.15 |
| mattcl-py | input-pting | 16.6 ± 0.8 | 15.7 | 19.6 | 13.59 ± 2.21 |
| mattcl-py | input-lanjian | 16.8 ± 3.4 | 15.6 | 61.5 | 13.76 ± 3.54 |
| pting | input-kcen | 16.9 ± 0.6 | 16.0 | 19.8 | 13.79 ± 2.20 |
| pting | input-pting | 16.9 ± 0.7 | 15.9 | 20.1 | 13.83 ± 2.22 |
| pting | input-lanjian | 16.9 ± 0.7 | 16.0 | 20.5 | 13.84 ± 2.22 |
| pting | input-chancalan | 17.0 ± 0.7 | 15.7 | 20.2 | 13.88 ± 2.23 |
| pting | input-mattcl | 17.0 ± 0.7 | 16.0 | 19.8 | 13.88 ± 2.23 |
| kcen | input-kcen | 20.1 ± 0.7 | 18.9 | 23.4 | 16.43 ± 2.63 |
| kcen | input-chancalan | 20.1 ± 0.6 | 18.9 | 22.8 | 16.45 ± 2.61 |
| kcen | input-pting | 20.2 ± 0.8 | 19.2 | 23.6 | 16.54 ± 2.66 |
| kcen | input-mattcl | 20.5 ± 2.3 | 19.1 | 42.8 | 16.72 ± 3.21 |
| kcen | input-lanjian | 20.6 ± 3.7 | 19.3 | 64.2 | 16.86 ± 4.02 |
| chancalan | input-mattcl | 24.3 ± 0.8 | 23.2 | 27.3 | 19.83 ± 3.15 |
| chancalan | input-lanjian | 24.3 ± 0.8 | 23.2 | 27.0 | 19.85 ± 3.16 |
| chancalan | input-pting | 24.3 ± 0.8 | 23.2 | 27.6 | 19.86 ± 3.16 |
| chancalan | input-chancalan | 24.3 ± 0.8 | 23.3 | 27.6 | 19.89 ± 3.18 |
| chancalan | input-kcen | 24.4 ± 0.9 | 23.2 | 27.0 | 19.92 ± 3.18 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|