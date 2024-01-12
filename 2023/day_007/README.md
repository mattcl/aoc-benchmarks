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
| lanjian | input-pting | 1.1 ± 4.1 | 0.2 | 58.0 | 1.00 |
| mattcl | input-pting | 1.1 ± 0.3 | 0.2 | 1.8 | 1.01 ± 3.83 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.01 ± 3.84 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.5 | 1.7 | 1.05 ± 3.96 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.05 ± 3.97 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.4 | 1.6 | 1.05 ± 3.99 |
| mattcl | input-lanjian | 1.1 ± 0.1 | 0.7 | 1.6 | 1.07 ± 4.03 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.6 | 1.07 ± 4.05 |
| lanjian | input-lanjian | 1.2 ± 0.1 | 0.5 | 1.6 | 1.07 ± 4.06 |
| lanjian | input-kcen | 1.2 ± 0.1 | 0.6 | 1.6 | 1.07 ± 4.07 |
| mattcl-ts | input-pting | 14.0 ± 0.4 | 12.9 | 15.7 | 13.08 ± 49.50 |
| mattcl-ts | input-chancalan | 14.1 ± 0.4 | 13.1 | 15.2 | 13.13 ± 49.69 |
| mattcl-ts | input-kcen | 14.1 ± 0.4 | 13.3 | 15.1 | 13.17 ± 49.84 |
| mattcl-ts | input-lanjian | 14.1 ± 0.4 | 13.2 | 14.8 | 13.17 ± 49.85 |
| mattcl-ts | input-mattcl | 14.1 ± 0.4 | 13.1 | 15.1 | 13.17 ± 49.87 |
| mattcl-py | input-pting | 16.4 ± 0.6 | 15.4 | 19.5 | 15.26 ± 57.77 |
| mattcl-py | input-chancalan | 16.4 ± 0.6 | 15.6 | 20.0 | 15.27 ± 57.80 |
| mattcl-py | input-kcen | 16.4 ± 0.7 | 15.2 | 19.9 | 15.29 ± 57.87 |
| mattcl-py | input-lanjian | 16.4 ± 0.7 | 15.7 | 19.5 | 15.32 ± 58.00 |
| mattcl-py | input-mattcl | 16.5 ± 0.8 | 15.7 | 21.7 | 15.36 ± 58.16 |
| pting | input-mattcl | 17.0 ± 0.6 | 16.0 | 20.5 | 15.79 ± 59.79 |
| pting | input-lanjian | 17.0 ± 0.6 | 16.3 | 19.9 | 15.86 ± 60.04 |
| pting | input-chancalan | 17.0 ± 0.6 | 16.0 | 20.3 | 15.86 ± 60.05 |
| pting | input-kcen | 17.1 ± 0.7 | 16.1 | 20.3 | 15.94 ± 60.34 |
| pting | input-pting | 17.2 ± 2.5 | 16.0 | 48.7 | 16.04 ± 60.75 |
| kcen | input-kcen | 20.0 ± 0.6 | 19.1 | 22.9 | 18.67 ± 70.66 |
| kcen | input-chancalan | 20.1 ± 0.6 | 18.9 | 22.8 | 18.69 ± 70.74 |
| kcen | input-lanjian | 20.1 ± 0.7 | 19.1 | 22.8 | 18.74 ± 70.94 |
| kcen | input-mattcl | 20.2 ± 0.7 | 19.3 | 23.2 | 18.83 ± 71.28 |
| kcen | input-pting | 20.3 ± 3.4 | 19.0 | 60.6 | 18.92 ± 71.68 |
| chancalan | input-kcen | 24.1 ± 0.7 | 22.7 | 26.9 | 22.44 ± 84.93 |
| chancalan | input-lanjian | 24.2 ± 0.8 | 23.2 | 27.5 | 22.55 ± 85.37 |
| chancalan | input-pting | 24.2 ± 0.8 | 23.1 | 27.2 | 22.58 ± 85.48 |
| chancalan | input-chancalan | 24.2 ± 0.7 | 23.0 | 27.1 | 22.58 ± 85.48 |
| chancalan | input-mattcl | 24.4 ± 1.0 | 22.8 | 27.5 | 22.68 ± 85.87 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|