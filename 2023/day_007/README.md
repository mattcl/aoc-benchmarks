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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.00 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.5 | 2.0 | 1.02 ± 0.25 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.4 | 2.0 | 1.02 ± 0.22 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 1.7 | 1.03 ± 0.21 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 1.8 | 1.03 ± 0.20 |
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.6 | 2.0 | 1.04 ± 0.22 |
| lanjian | input-mattcl | 1.3 ± 0.1 | 0.7 | 1.7 | 1.04 ± 0.19 |
| mattcl | input-lanjian | 1.3 ± 0.1 | 0.6 | 1.7 | 1.05 ± 0.20 |
| lanjian | input-kcen | 1.3 ± 0.1 | 0.8 | 1.8 | 1.05 ± 0.20 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.7 | 1.9 | 1.06 ± 0.21 |
| mattcl-ts | input-lanjian | 14.6 ± 0.4 | 13.4 | 15.5 | 11.86 ± 1.79 |
| mattcl-ts | input-mattcl | 14.6 ± 0.4 | 13.7 | 15.9 | 11.90 ± 1.79 |
| mattcl-ts | input-kcen | 14.6 ± 0.4 | 13.6 | 16.2 | 11.91 ± 1.79 |
| mattcl-ts | input-pting | 14.6 ± 0.4 | 13.7 | 15.7 | 11.92 ± 1.80 |
| mattcl-ts | input-chancalan | 14.7 ± 0.3 | 13.7 | 15.8 | 11.94 ± 1.79 |
| mattcl-py | input-pting | 16.7 ± 0.7 | 15.7 | 19.7 | 13.62 ± 2.10 |
| mattcl-py | input-mattcl | 16.8 ± 0.7 | 15.6 | 20.3 | 13.64 ± 2.10 |
| mattcl-py | input-chancalan | 16.8 ± 0.7 | 15.9 | 19.8 | 13.68 ± 2.11 |
| mattcl-py | input-kcen | 16.9 ± 0.8 | 15.6 | 20.0 | 13.72 ± 2.13 |
| mattcl-py | input-lanjian | 16.9 ± 0.7 | 15.7 | 20.4 | 13.75 ± 2.12 |
| pting | input-mattcl | 17.1 ± 0.6 | 16.0 | 19.9 | 13.90 ± 2.12 |
| pting | input-lanjian | 17.1 ± 0.5 | 16.2 | 19.3 | 13.96 ± 2.12 |
| pting | input-chancalan | 17.2 ± 0.6 | 16.2 | 19.9 | 13.97 ± 2.13 |
| pting | input-pting | 17.2 ± 0.6 | 16.3 | 19.9 | 13.97 ± 2.14 |
| pting | input-kcen | 17.3 ± 0.7 | 16.1 | 20.3 | 14.09 ± 2.18 |
| kcen | input-chancalan | 20.4 ± 0.7 | 18.9 | 23.7 | 16.60 ± 2.53 |
| kcen | input-pting | 20.4 ± 0.6 | 19.5 | 22.5 | 16.62 ± 2.51 |
| kcen | input-mattcl | 20.5 ± 0.6 | 19.4 | 23.4 | 16.68 ± 2.53 |
| kcen | input-kcen | 20.5 ± 0.8 | 19.4 | 23.7 | 16.72 ± 2.57 |
| kcen | input-lanjian | 20.6 ± 0.7 | 19.1 | 23.2 | 16.78 ± 2.56 |
| chancalan | input-pting | 24.5 ± 0.9 | 23.4 | 27.8 | 19.97 ± 3.06 |
| chancalan | input-mattcl | 24.5 ± 0.8 | 23.3 | 27.9 | 19.98 ± 3.03 |
| chancalan | input-kcen | 24.6 ± 0.8 | 23.2 | 27.7 | 20.03 ± 3.04 |
| chancalan | input-chancalan | 24.6 ± 0.7 | 23.0 | 27.3 | 20.03 ± 3.03 |
| chancalan | input-lanjian | 24.7 ± 0.7 | 23.7 | 27.5 | 20.13 ± 3.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|