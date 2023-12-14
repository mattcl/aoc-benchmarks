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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.5 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.26 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.26 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.2 | 1.6 | 1.03 ± 0.27 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.2 | 1.4 | 1.03 ± 0.26 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.6 | 1.04 ± 0.28 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.6 | 1.04 ± 0.27 |
| lanjian | input-kcen | 1.1 ± 0.1 | 0.5 | 1.3 | 1.05 ± 0.25 |
| lanjian | input-lanjian | 1.1 ± 0.1 | 0.6 | 1.3 | 1.07 ± 0.25 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.4 | 1.7 | 1.09 ± 0.28 |
| mattcl-ts | input-lanjian | 14.8 ± 0.4 | 14.0 | 16.8 | 14.05 ± 2.76 |
| mattcl-ts | input-pting | 14.8 ± 0.4 | 13.9 | 16.4 | 14.05 ± 2.77 |
| mattcl-ts | input-kcen | 14.8 ± 0.3 | 13.8 | 15.8 | 14.07 ± 2.76 |
| mattcl-ts | input-chancalan | 14.8 ± 0.4 | 13.9 | 16.8 | 14.09 ± 2.77 |
| mattcl-ts | input-mattcl | 15.2 ± 3.6 | 13.9 | 63.5 | 14.45 ± 4.44 |
| mattcl-py | input-chancalan | 16.4 ± 0.5 | 15.7 | 19.0 | 15.60 ± 3.08 |
| mattcl-py | input-kcen | 16.4 ± 0.7 | 15.4 | 19.7 | 15.61 ± 3.11 |
| mattcl-py | input-lanjian | 16.4 ± 0.6 | 15.5 | 19.2 | 15.62 ± 3.10 |
| mattcl-py | input-mattcl | 16.5 ± 0.5 | 15.6 | 18.1 | 15.66 ± 3.10 |
| mattcl-py | input-pting | 16.5 ± 0.6 | 15.5 | 19.5 | 15.67 ± 3.12 |
| pting | input-pting | 16.9 ± 0.6 | 16.1 | 19.7 | 16.08 ± 3.19 |
| pting | input-lanjian | 16.9 ± 0.7 | 16.2 | 20.5 | 16.08 ± 3.20 |
| pting | input-kcen | 16.9 ± 0.6 | 16.1 | 19.5 | 16.09 ± 3.19 |
| pting | input-mattcl | 17.0 ± 0.7 | 16.1 | 20.5 | 16.12 ± 3.22 |
| pting | input-chancalan | 17.0 ± 0.7 | 16.0 | 20.4 | 16.14 ± 3.22 |
| kcen | input-chancalan | 20.2 ± 0.8 | 19.2 | 23.0 | 19.15 ± 3.81 |
| kcen | input-pting | 20.2 ± 0.7 | 19.2 | 22.6 | 19.20 ± 3.80 |
| kcen | input-mattcl | 20.3 ± 0.7 | 19.3 | 23.0 | 19.27 ± 3.83 |
| kcen | input-kcen | 20.3 ± 0.8 | 19.0 | 23.1 | 19.32 ± 3.85 |
| kcen | input-lanjian | 20.4 ± 1.8 | 19.2 | 39.9 | 19.34 ± 4.14 |
| chancalan | input-lanjian | 24.2 ± 0.8 | 22.8 | 27.0 | 22.99 ± 4.54 |
| chancalan | input-chancalan | 24.2 ± 0.7 | 23.2 | 26.7 | 23.03 ± 4.55 |
| chancalan | input-pting | 24.3 ± 0.7 | 23.2 | 27.5 | 23.08 ± 4.55 |
| chancalan | input-mattcl | 24.3 ± 0.8 | 22.9 | 27.6 | 23.11 ± 4.57 |
| chancalan | input-kcen | 24.4 ± 0.8 | 23.2 | 27.3 | 23.21 ± 4.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|