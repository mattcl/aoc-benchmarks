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
| mattcl | input-chancalan | 1.0 ± 0.3 | 0.3 | 1.6 | 1.00 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.11 ± 0.36 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.5 | 1.9 | 1.11 ± 0.36 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.6 | 1.12 ± 0.35 |
| mattcl | input-pting | 1.1 ± 0.1 | 0.5 | 1.6 | 1.13 ± 0.34 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.5 | 1.6 | 1.13 ± 0.36 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.14 ± 0.35 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.9 | 1.16 ± 0.36 |
| lanjian | input-kcen | 1.2 ± 0.1 | 0.6 | 1.7 | 1.17 ± 0.35 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.8 | 1.19 ± 0.37 |
| mattcl-ts | input-pting | 14.7 ± 0.3 | 13.6 | 15.5 | 14.69 ± 4.01 |
| mattcl-ts | input-kcen | 14.7 ± 0.4 | 13.8 | 15.6 | 14.70 ± 4.02 |
| mattcl-ts | input-lanjian | 14.7 ± 0.4 | 13.7 | 15.7 | 14.71 ± 4.02 |
| mattcl-ts | input-mattcl | 14.7 ± 0.4 | 13.7 | 15.9 | 14.77 ± 4.04 |
| mattcl-ts | input-chancalan | 15.1 ± 0.6 | 14.0 | 18.7 | 15.18 ± 4.17 |
| mattcl-py | input-mattcl | 16.8 ± 0.6 | 15.5 | 19.9 | 16.81 ± 4.62 |
| mattcl-py | input-lanjian | 16.8 ± 0.5 | 15.9 | 19.0 | 16.87 ± 4.62 |
| mattcl-py | input-kcen | 16.9 ± 0.7 | 15.4 | 19.7 | 16.91 ± 4.66 |
| mattcl-py | input-pting | 17.1 ± 3.4 | 15.6 | 61.7 | 17.11 ± 5.77 |
| mattcl-py | input-chancalan | 17.2 ± 0.6 | 16.1 | 21.0 | 17.27 ± 4.75 |
| pting | input-pting | 17.3 ± 0.7 | 16.1 | 20.2 | 17.37 ± 4.78 |
| pting | input-kcen | 17.4 ± 0.7 | 16.2 | 20.5 | 17.39 ± 4.79 |
| pting | input-mattcl | 17.4 ± 0.8 | 15.8 | 20.4 | 17.44 ± 4.82 |
| pting | input-lanjian | 17.4 ± 0.7 | 16.3 | 20.7 | 17.44 ± 4.80 |
| pting | input-chancalan | 17.5 ± 0.8 | 16.3 | 20.4 | 17.54 ± 4.83 |
| kcen | input-pting | 20.5 ± 0.6 | 19.6 | 23.8 | 20.54 ± 5.63 |
| kcen | input-lanjian | 20.6 ± 0.8 | 18.9 | 23.4 | 20.62 ± 5.67 |
| kcen | input-kcen | 20.6 ± 0.9 | 19.6 | 23.7 | 20.67 ± 5.69 |
| kcen | input-mattcl | 20.7 ± 0.9 | 19.6 | 28.3 | 20.72 ± 5.71 |
| kcen | input-chancalan | 21.5 ± 1.5 | 20.6 | 37.5 | 21.57 ± 6.05 |
| chancalan | input-kcen | 24.7 ± 0.8 | 23.6 | 27.2 | 24.74 ± 6.77 |
| chancalan | input-mattcl | 24.7 ± 0.8 | 23.2 | 27.6 | 24.75 ± 6.78 |
| chancalan | input-pting | 24.7 ± 0.9 | 23.4 | 28.0 | 24.77 ± 6.80 |
| chancalan | input-lanjian | 24.7 ± 0.8 | 22.9 | 27.9 | 24.78 ± 6.79 |
| chancalan | input-chancalan | 25.7 ± 0.6 | 24.6 | 28.3 | 25.75 ± 7.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|