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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 ± 0.24 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.23 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.5 | 1.7 | 1.02 ± 0.21 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.5 | 1.6 | 1.02 ± 0.22 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.22 |
| lanjian | input-pting | 1.2 ± 0.1 | 0.3 | 1.6 | 1.04 ± 0.20 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.9 | 1.04 ± 0.25 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 2.0 | 1.07 ± 0.25 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 2.0 | 1.07 ± 0.23 |
| mattcl-ts | input-lanjian | 15.0 ± 0.4 | 13.8 | 16.0 | 13.03 ± 2.12 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 13.9 | 16.2 | 13.05 ± 2.12 |
| mattcl-ts | input-kcen | 15.0 ± 0.3 | 14.1 | 16.3 | 13.05 ± 2.11 |
| mattcl-ts | input-pting | 15.1 ± 0.4 | 13.8 | 16.1 | 13.09 ± 2.13 |
| mattcl-ts | input-chancalan | 15.3 ± 3.8 | 14.1 | 67.8 | 13.27 ± 3.93 |
| mattcl-py | input-mattcl | 16.6 ± 0.6 | 15.4 | 19.4 | 14.47 ± 2.37 |
| mattcl-py | input-lanjian | 16.7 ± 0.6 | 15.8 | 19.2 | 14.52 ± 2.40 |
| mattcl-py | input-kcen | 16.8 ± 0.7 | 15.2 | 20.1 | 14.60 ± 2.43 |
| mattcl-py | input-pting | 16.8 ± 0.8 | 15.5 | 19.8 | 14.61 ± 2.44 |
| mattcl-py | input-chancalan | 17.0 ± 3.3 | 15.5 | 58.4 | 14.80 ± 3.70 |
| pting | input-mattcl | 17.2 ± 0.5 | 16.3 | 19.5 | 14.94 ± 2.44 |
| pting | input-chancalan | 17.2 ± 0.7 | 16.3 | 20.5 | 14.95 ± 2.47 |
| pting | input-kcen | 17.3 ± 0.7 | 15.8 | 20.0 | 15.04 ± 2.49 |
| pting | input-pting | 17.3 ± 0.8 | 16.2 | 20.5 | 15.05 ± 2.51 |
| pting | input-lanjian | 17.3 ± 0.7 | 16.0 | 20.9 | 15.05 ± 2.49 |
| kcen | input-kcen | 20.4 ± 0.7 | 19.2 | 23.5 | 17.78 ± 2.93 |
| kcen | input-mattcl | 20.5 ± 0.6 | 19.4 | 23.6 | 17.83 ± 2.91 |
| kcen | input-pting | 20.5 ± 0.7 | 19.2 | 23.2 | 17.83 ± 2.92 |
| kcen | input-chancalan | 20.5 ± 0.8 | 19.5 | 23.5 | 17.87 ± 2.94 |
| kcen | input-lanjian | 20.6 ± 0.9 | 19.5 | 24.0 | 17.93 ± 2.97 |
| chancalan | input-lanjian | 24.6 ± 0.7 | 23.6 | 27.8 | 21.36 ± 3.49 |
| chancalan | input-mattcl | 24.6 ± 0.8 | 22.8 | 27.6 | 21.39 ± 3.50 |
| chancalan | input-kcen | 24.7 ± 1.0 | 23.1 | 28.1 | 21.45 ± 3.54 |
| chancalan | input-pting | 24.7 ± 0.8 | 23.2 | 27.6 | 21.52 ± 3.52 |
| chancalan | input-chancalan | 24.8 ± 0.8 | 22.9 | 27.8 | 21.59 ± 3.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|