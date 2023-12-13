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
| mattcl | input-pting | 1.0 ± 0.3 | 0.3 | 1.4 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.9 | 1.24 ± 0.46 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.25 ± 0.46 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.8 | 1.26 ± 0.46 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.5 | 1.7 | 1.26 ± 0.46 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.6 | 1.8 | 1.27 ± 0.47 |
| lanjian | input-pting | 1.3 ± 0.1 | 0.4 | 1.7 | 1.28 ± 0.46 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.3 | 1.8 | 1.28 ± 0.47 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.4 | 2.0 | 1.31 ± 0.49 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.5 | 1.8 | 1.32 ± 0.47 |
| mattcl-ts | input-kcen | 15.1 ± 0.4 | 14.2 | 16.4 | 15.33 ± 5.20 |
| mattcl-ts | input-pting | 15.1 ± 0.4 | 14.4 | 16.4 | 15.35 ± 5.20 |
| mattcl-ts | input-chancalan | 15.1 ± 0.4 | 14.0 | 18.3 | 15.38 ± 5.22 |
| mattcl-ts | input-mattcl | 15.4 ± 3.6 | 14.3 | 65.5 | 15.61 ± 6.45 |
| mattcl-ts | input-lanjian | 16.0 ± 6.1 | 14.1 | 68.8 | 16.30 ± 8.31 |
| mattcl-py | input-chancalan | 16.8 ± 0.6 | 15.5 | 20.4 | 17.08 ± 5.81 |
| mattcl-py | input-pting | 16.8 ± 0.6 | 15.6 | 19.9 | 17.09 ± 5.82 |
| mattcl-py | input-mattcl | 16.9 ± 0.7 | 16.0 | 19.8 | 17.19 ± 5.86 |
| mattcl-py | input-kcen | 16.9 ± 0.7 | 15.8 | 19.7 | 17.21 ± 5.87 |
| mattcl-py | input-lanjian | 17.0 ± 0.8 | 15.8 | 19.8 | 17.32 ± 5.91 |
| pting | input-mattcl | 17.4 ± 0.5 | 16.3 | 20.4 | 17.64 ± 5.99 |
| pting | input-kcen | 17.4 ± 0.6 | 16.3 | 19.8 | 17.70 ± 6.02 |
| pting | input-chancalan | 17.4 ± 0.7 | 16.1 | 20.7 | 17.70 ± 6.03 |
| pting | input-lanjian | 17.5 ± 0.8 | 15.9 | 20.9 | 17.77 ± 6.07 |
| pting | input-pting | 17.5 ± 0.8 | 16.2 | 20.1 | 17.80 ± 6.07 |
| kcen | input-pting | 20.5 ± 0.6 | 19.2 | 23.5 | 20.87 ± 7.08 |
| kcen | input-kcen | 20.6 ± 0.6 | 19.3 | 23.5 | 20.93 ± 7.11 |
| kcen | input-lanjian | 20.7 ± 0.6 | 19.6 | 23.0 | 20.99 ± 7.13 |
| kcen | input-mattcl | 20.7 ± 0.7 | 19.2 | 23.8 | 21.06 ± 7.16 |
| kcen | input-chancalan | 20.8 ± 0.8 | 19.3 | 23.7 | 21.09 ± 7.18 |
| chancalan | input-mattcl | 24.5 ± 0.6 | 23.4 | 27.4 | 24.91 ± 8.45 |
| chancalan | input-pting | 24.6 ± 0.8 | 23.5 | 27.6 | 25.04 ± 8.51 |
| chancalan | input-lanjian | 24.6 ± 0.8 | 23.5 | 28.1 | 25.05 ± 8.52 |
| chancalan | input-chancalan | 24.7 ± 0.7 | 23.4 | 27.1 | 25.12 ± 8.53 |
| chancalan | input-kcen | 24.9 ± 0.8 | 23.6 | 28.3 | 25.30 ± 8.60 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|