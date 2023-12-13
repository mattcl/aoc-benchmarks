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
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.2 | 1.6 | 1.00 ± 0.24 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.4 | 2.0 | 1.01 ± 0.23 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.4 | 2.0 | 1.01 ± 0.24 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.3 | 1.8 | 1.02 ± 0.26 |
| mattcl | input-pting | 1.1 ± 0.1 | 0.4 | 1.6 | 1.02 ± 0.22 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.2 | 1.9 | 1.02 ± 0.25 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.4 | 1.9 | 1.03 ± 0.26 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.6 | 1.6 | 1.03 ± 0.24 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.2 | 1.7 | 1.03 ± 0.25 |
| mattcl-ts | input-pting | 14.9 ± 0.3 | 14.2 | 15.9 | 13.51 ± 2.32 |
| mattcl-ts | input-kcen | 14.9 ± 0.4 | 14.0 | 16.1 | 13.52 ± 2.33 |
| mattcl-ts | input-chancalan | 14.9 ± 0.4 | 13.9 | 15.9 | 13.53 ± 2.33 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 14.0 | 16.1 | 13.53 ± 2.33 |
| mattcl-ts | input-lanjian | 15.0 ± 0.4 | 14.0 | 16.0 | 13.54 ± 2.33 |
| mattcl-py | input-chancalan | 16.6 ± 0.6 | 15.4 | 19.0 | 15.01 ± 2.61 |
| mattcl-py | input-lanjian | 16.7 ± 0.6 | 15.7 | 19.0 | 15.12 ± 2.63 |
| mattcl-py | input-pting | 16.7 ± 0.7 | 15.4 | 20.0 | 15.14 ± 2.65 |
| mattcl-py | input-kcen | 16.7 ± 0.7 | 15.5 | 20.2 | 15.15 ± 2.65 |
| mattcl-py | input-mattcl | 16.8 ± 0.7 | 15.6 | 20.0 | 15.20 ± 2.67 |
| pting | input-chancalan | 17.2 ± 0.5 | 16.3 | 18.9 | 15.56 ± 2.69 |
| pting | input-kcen | 17.3 ± 0.7 | 16.0 | 20.5 | 15.62 ± 2.73 |
| pting | input-pting | 17.3 ± 0.7 | 16.3 | 20.6 | 15.64 ± 2.74 |
| pting | input-mattcl | 17.3 ± 0.6 | 16.4 | 20.2 | 15.66 ± 2.73 |
| pting | input-lanjian | 17.3 ± 0.7 | 16.3 | 20.0 | 15.67 ± 2.74 |
| kcen | input-lanjian | 20.4 ± 0.7 | 19.1 | 23.9 | 18.44 ± 3.20 |
| kcen | input-pting | 20.5 ± 0.6 | 19.5 | 23.5 | 18.57 ± 3.22 |
| kcen | input-mattcl | 20.5 ± 0.8 | 19.5 | 23.5 | 18.59 ± 3.24 |
| kcen | input-chancalan | 20.6 ± 0.8 | 19.4 | 23.3 | 18.60 ± 3.25 |
| kcen | input-kcen | 20.9 ± 3.4 | 19.0 | 58.5 | 18.96 ± 4.46 |
| chancalan | input-kcen | 24.5 ± 0.9 | 23.1 | 28.0 | 22.18 ± 3.86 |
| chancalan | input-mattcl | 24.5 ± 0.9 | 22.9 | 28.0 | 22.21 ± 3.87 |
| chancalan | input-chancalan | 24.7 ± 0.8 | 23.5 | 27.4 | 22.37 ± 3.88 |
| chancalan | input-lanjian | 24.7 ± 1.0 | 23.3 | 27.8 | 22.38 ± 3.92 |
| chancalan | input-pting | 24.8 ± 0.9 | 23.4 | 27.9 | 22.41 ± 3.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|