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
| mattcl | input-mattcl | 1.1 ± 0.3 | 0.4 | 1.8 | 1.00 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.31 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.8 | 1.08 ± 0.30 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.7 | 1.08 ± 0.30 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.7 | 1.7 | 1.09 ± 0.29 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.09 ± 0.30 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.6 | 1.8 | 1.09 ± 0.29 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.10 ± 0.29 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 2.1 | 1.13 ± 0.32 |
| lanjian | input-mattcl | 1.2 ± 0.1 | 0.7 | 1.7 | 1.13 ± 0.29 |
| mattcl-ts | input-kcen | 14.8 ± 0.4 | 13.7 | 16.4 | 13.48 ± 3.13 |
| mattcl-ts | input-pting | 14.9 ± 0.3 | 14.1 | 16.0 | 13.52 ± 3.13 |
| mattcl-ts | input-lanjian | 14.9 ± 0.3 | 14.1 | 16.0 | 13.53 ± 3.13 |
| mattcl-ts | input-chancalan | 14.9 ± 0.3 | 14.0 | 15.8 | 13.54 ± 3.14 |
| mattcl-ts | input-mattcl | 15.5 ± 5.3 | 14.0 | 72.1 | 14.05 ± 5.83 |
| mattcl-py | input-kcen | 16.5 ± 0.6 | 15.7 | 20.3 | 14.94 ± 3.48 |
| mattcl-py | input-pting | 16.5 ± 0.6 | 15.7 | 19.5 | 14.98 ± 3.49 |
| mattcl-py | input-chancalan | 16.5 ± 0.7 | 15.4 | 18.9 | 15.00 ± 3.51 |
| mattcl-py | input-lanjian | 16.6 ± 0.6 | 15.6 | 19.4 | 15.03 ± 3.51 |
| pting | input-kcen | 16.9 ± 0.7 | 16.1 | 21.0 | 15.35 ± 3.59 |
| pting | input-lanjian | 16.9 ± 0.6 | 16.1 | 20.6 | 15.37 ± 3.59 |
| pting | input-chancalan | 17.0 ± 0.6 | 16.1 | 19.6 | 15.40 ± 3.59 |
| pting | input-mattcl | 17.0 ± 0.6 | 16.1 | 20.7 | 15.44 ± 3.59 |
| pting | input-pting | 17.0 ± 0.7 | 16.2 | 20.1 | 15.48 ± 3.62 |
| mattcl-py | input-mattcl | 17.4 ± 6.3 | 15.6 | 71.2 | 15.84 ± 6.80 |
| kcen | input-pting | 20.2 ± 0.6 | 19.1 | 22.8 | 18.38 ± 4.27 |
| kcen | input-kcen | 20.3 ± 0.7 | 19.2 | 23.0 | 18.44 ± 4.30 |
| kcen | input-mattcl | 20.3 ± 0.6 | 19.2 | 22.9 | 18.45 ± 4.29 |
| kcen | input-chancalan | 20.3 ± 0.8 | 19.4 | 24.0 | 18.47 ± 4.32 |
| kcen | input-lanjian | 20.4 ± 0.7 | 19.3 | 23.1 | 18.49 ± 4.31 |
| chancalan | input-pting | 24.3 ± 0.6 | 23.3 | 26.8 | 22.04 ± 5.11 |
| chancalan | input-lanjian | 24.5 ± 0.8 | 23.5 | 28.1 | 22.23 ± 5.18 |
| chancalan | input-mattcl | 24.5 ± 0.8 | 23.4 | 28.2 | 22.28 ± 5.19 |
| chancalan | input-chancalan | 24.6 ± 0.8 | 23.3 | 27.3 | 22.29 ± 5.19 |
| chancalan | input-kcen | 24.6 ± 1.0 | 23.3 | 27.1 | 22.32 ± 5.22 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|