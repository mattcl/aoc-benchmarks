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
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.6 | 1.6 | 1.00 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.8 | 1.01 ± 0.21 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.7 | 1.01 ± 0.20 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.01 ± 0.20 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.02 ± 0.21 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.5 | 1.9 | 1.03 ± 0.23 |
| lanjian | input-pting | 1.2 ± 0.1 | 0.4 | 1.8 | 1.04 ± 0.20 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.7 | 2.1 | 1.04 ± 0.21 |
| lanjian | input-mattcl | 1.2 ± 0.1 | 0.6 | 1.7 | 1.04 ± 0.19 |
| lanjian | input-lanjian | 1.2 ± 0.1 | 0.9 | 1.7 | 1.05 ± 0.18 |
| mattcl-ts | input-chancalan | 15.0 ± 0.3 | 14.1 | 15.8 | 12.95 ± 1.89 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 14.2 | 16.5 | 12.98 ± 1.90 |
| mattcl-ts | input-pting | 15.0 ± 0.3 | 14.3 | 15.9 | 13.00 ± 1.90 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 14.1 | 15.9 | 13.01 ± 1.90 |
| mattcl-ts | input-kcen | 15.1 ± 0.4 | 14.3 | 16.2 | 13.03 ± 1.90 |
| mattcl-py | input-pting | 16.7 ± 0.6 | 15.4 | 19.6 | 14.48 ± 2.16 |
| mattcl-py | input-lanjian | 16.8 ± 0.7 | 15.5 | 19.7 | 14.52 ± 2.17 |
| mattcl-py | input-chancalan | 16.8 ± 0.7 | 15.4 | 19.6 | 14.54 ± 2.18 |
| mattcl-py | input-mattcl | 16.8 ± 0.8 | 15.4 | 20.5 | 14.56 ± 2.20 |
| mattcl-py | input-kcen | 16.8 ± 0.6 | 15.5 | 19.6 | 14.57 ± 2.16 |
| pting | input-kcen | 17.3 ± 0.5 | 16.2 | 19.9 | 14.93 ± 2.20 |
| pting | input-pting | 17.3 ± 0.6 | 16.0 | 19.9 | 14.96 ± 2.22 |
| pting | input-chancalan | 17.3 ± 0.5 | 16.5 | 20.7 | 14.97 ± 2.21 |
| pting | input-lanjian | 17.4 ± 0.7 | 16.1 | 20.7 | 15.03 ± 2.25 |
| pting | input-mattcl | 17.4 ± 0.6 | 16.4 | 20.8 | 15.04 ± 2.24 |
| kcen | input-chancalan | 20.5 ± 0.6 | 19.4 | 23.0 | 17.68 ± 2.60 |
| kcen | input-pting | 20.5 ± 0.8 | 19.5 | 23.1 | 17.75 ± 2.64 |
| kcen | input-kcen | 20.6 ± 0.8 | 19.4 | 23.8 | 17.83 ± 2.66 |
| kcen | input-mattcl | 20.7 ± 1.4 | 19.5 | 35.9 | 17.86 ± 2.84 |
| kcen | input-lanjian | 20.8 ± 0.8 | 19.8 | 23.4 | 17.98 ± 2.67 |
| chancalan | input-chancalan | 24.6 ± 0.8 | 23.1 | 27.3 | 21.26 ± 3.15 |
| chancalan | input-pting | 24.6 ± 0.8 | 23.4 | 27.7 | 21.30 ± 3.14 |
| chancalan | input-mattcl | 24.7 ± 0.8 | 23.4 | 27.7 | 21.36 ± 3.16 |
| chancalan | input-kcen | 24.7 ± 0.9 | 23.6 | 28.4 | 21.37 ± 3.18 |
| chancalan | input-lanjian | 24.8 ± 0.8 | 23.5 | 28.1 | 21.40 ± 3.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|