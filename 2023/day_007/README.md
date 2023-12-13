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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.25 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.23 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.5 | 1.7 | 1.03 ± 0.24 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.25 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.5 | 1.8 | 1.04 ± 0.25 |
| lanjian | input-kcen | 1.1 ± 0.1 | 0.6 | 1.6 | 1.05 ± 0.22 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.2 | 1.6 | 1.05 ± 0.25 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.8 | 1.05 ± 0.26 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.9 | 1.07 ± 0.26 |
| mattcl-ts | input-pting | 14.9 ± 0.3 | 14.1 | 16.0 | 13.81 ± 2.48 |
| mattcl-ts | input-chancalan | 14.9 ± 0.4 | 14.1 | 16.3 | 13.85 ± 2.49 |
| mattcl-ts | input-kcen | 15.0 ± 0.4 | 14.0 | 15.9 | 13.86 ± 2.49 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 14.0 | 16.1 | 13.89 ± 2.49 |
| mattcl-ts | input-lanjian | 15.0 ± 0.4 | 13.9 | 16.0 | 13.90 ± 2.50 |
| mattcl-py | input-mattcl | 16.7 ± 0.7 | 15.6 | 19.6 | 15.49 ± 2.82 |
| mattcl-py | input-pting | 16.7 ± 0.6 | 15.9 | 20.0 | 15.50 ± 2.82 |
| mattcl-py | input-chancalan | 16.7 ± 0.6 | 15.4 | 19.5 | 15.51 ± 2.82 |
| mattcl-py | input-lanjian | 16.9 ± 0.8 | 15.9 | 20.2 | 15.64 ± 2.87 |
| mattcl-py | input-kcen | 16.9 ± 0.8 | 15.8 | 20.4 | 15.64 ± 2.87 |
| pting | input-pting | 17.2 ± 0.6 | 16.0 | 19.9 | 15.97 ± 2.89 |
| pting | input-chancalan | 17.3 ± 0.7 | 16.1 | 20.6 | 15.99 ± 2.91 |
| pting | input-lanjian | 17.3 ± 0.7 | 16.3 | 20.9 | 16.04 ± 2.93 |
| pting | input-kcen | 17.4 ± 0.7 | 16.1 | 20.7 | 16.09 ± 2.93 |
| pting | input-mattcl | 17.4 ± 1.5 | 16.1 | 34.5 | 16.11 ± 3.18 |
| kcen | input-pting | 20.4 ± 0.7 | 18.9 | 24.0 | 18.90 ± 3.42 |
| kcen | input-chancalan | 20.5 ± 0.7 | 18.8 | 23.2 | 18.97 ± 3.44 |
| kcen | input-mattcl | 20.5 ± 0.7 | 19.5 | 24.6 | 19.02 ± 3.45 |
| kcen | input-kcen | 20.5 ± 0.8 | 19.0 | 23.8 | 19.03 ± 3.46 |
| kcen | input-lanjian | 20.6 ± 0.7 | 19.3 | 23.5 | 19.08 ± 3.46 |
| chancalan | input-chancalan | 24.5 ± 0.8 | 23.0 | 27.1 | 22.71 ± 4.10 |
| chancalan | input-lanjian | 24.6 ± 0.7 | 23.5 | 27.9 | 22.76 ± 4.09 |
| chancalan | input-mattcl | 24.6 ± 0.8 | 23.2 | 27.7 | 22.79 ± 4.12 |
| chancalan | input-kcen | 24.7 ± 0.7 | 23.7 | 27.5 | 22.85 ± 4.12 |
| chancalan | input-pting | 24.7 ± 0.8 | 23.4 | 27.9 | 22.88 ± 4.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|