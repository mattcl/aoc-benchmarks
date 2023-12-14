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
| mattcl | input-chancalan | 1.2 ± 0.1 | 0.7 | 1.6 | 1.04 ± 0.21 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 2.7 | 1.05 ± 0.25 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.7 | 1.06 ± 0.23 |
| mattcl | input-kcen | 1.3 ± 0.1 | 0.4 | 1.8 | 1.06 ± 0.22 |
| mattcl | input-mattcl | 1.3 ± 0.1 | 0.7 | 1.8 | 1.06 ± 0.22 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.8 | 1.07 ± 0.23 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.6 | 2.0 | 1.08 ± 0.24 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.8 | 1.09 ± 0.22 |
| lanjian | input-kcen | 1.3 ± 0.1 | 0.6 | 1.8 | 1.09 ± 0.22 |
| mattcl-ts | input-chancalan | 15.0 ± 0.4 | 14.2 | 16.1 | 12.71 ± 2.15 |
| mattcl-ts | input-pting | 15.1 ± 0.3 | 14.1 | 16.0 | 12.74 ± 2.15 |
| mattcl-ts | input-kcen | 15.1 ± 0.4 | 14.1 | 16.3 | 12.74 ± 2.15 |
| mattcl-ts | input-mattcl | 15.1 ± 0.4 | 14.2 | 16.1 | 12.76 ± 2.15 |
| mattcl-ts | input-lanjian | 15.3 ± 3.1 | 14.3 | 56.8 | 12.95 ± 3.40 |
| mattcl-py | input-pting | 16.8 ± 0.6 | 15.5 | 20.2 | 14.20 ± 2.42 |
| mattcl-py | input-kcen | 16.8 ± 0.7 | 15.9 | 20.3 | 14.22 ± 2.44 |
| mattcl-py | input-chancalan | 16.9 ± 0.6 | 15.9 | 19.6 | 14.28 ± 2.44 |
| mattcl-py | input-lanjian | 16.9 ± 0.6 | 15.8 | 19.6 | 14.30 ± 2.44 |
| mattcl-py | input-mattcl | 17.0 ± 0.7 | 15.8 | 19.9 | 14.34 ± 2.47 |
| pting | input-pting | 17.3 ± 0.7 | 16.2 | 20.8 | 14.61 ± 2.50 |
| pting | input-kcen | 17.4 ± 0.7 | 16.2 | 20.4 | 14.69 ± 2.53 |
| pting | input-chancalan | 17.4 ± 0.8 | 16.4 | 21.1 | 14.71 ± 2.54 |
| pting | input-mattcl | 17.4 ± 0.7 | 16.3 | 19.8 | 14.72 ± 2.53 |
| pting | input-lanjian | 17.6 ± 3.5 | 16.2 | 61.6 | 14.91 ± 3.86 |
| kcen | input-pting | 20.5 ± 0.6 | 19.4 | 23.4 | 17.33 ± 2.93 |
| kcen | input-mattcl | 20.6 ± 0.7 | 19.1 | 23.8 | 17.42 ± 2.97 |
| kcen | input-chancalan | 20.6 ± 0.8 | 19.2 | 24.1 | 17.43 ± 2.99 |
| kcen | input-lanjian | 20.6 ± 0.7 | 19.3 | 24.0 | 17.46 ± 2.98 |
| kcen | input-kcen | 20.7 ± 0.7 | 19.6 | 23.3 | 17.47 ± 2.97 |
| chancalan | input-lanjian | 24.7 ± 0.9 | 23.4 | 28.1 | 20.87 ± 3.57 |
| chancalan | input-chancalan | 24.7 ± 0.8 | 23.1 | 27.6 | 20.87 ± 3.55 |
| chancalan | input-kcen | 24.7 ± 0.7 | 23.5 | 27.2 | 20.88 ± 3.54 |
| chancalan | input-pting | 24.7 ± 0.9 | 23.3 | 27.6 | 20.90 ± 3.57 |
| chancalan | input-mattcl | 25.3 ± 3.1 | 23.3 | 51.1 | 21.36 ± 4.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|