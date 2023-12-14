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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.8 | 1.02 ± 0.24 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.23 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.7 | 1.03 ± 0.24 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.23 |
| lanjian | input-pting | 1.2 ± 0.1 | 0.7 | 1.7 | 1.05 ± 0.21 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.7 | 1.9 | 1.06 ± 0.22 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.7 | 2.0 | 1.06 ± 0.22 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.8 | 1.06 ± 0.23 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.7 | 2.1 | 1.07 ± 0.22 |
| mattcl-ts | input-chancalan | 14.9 ± 0.3 | 13.9 | 15.8 | 12.71 ± 2.12 |
| mattcl-ts | input-kcen | 14.9 ± 0.4 | 14.0 | 16.1 | 12.73 ± 2.13 |
| mattcl-ts | input-pting | 15.0 ± 0.3 | 14.1 | 16.0 | 12.76 ± 2.13 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 13.9 | 15.9 | 12.77 ± 2.13 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 13.9 | 16.2 | 12.77 ± 2.14 |
| mattcl-py | input-lanjian | 16.6 ± 0.7 | 15.5 | 19.7 | 14.20 ± 2.42 |
| mattcl-py | input-mattcl | 16.7 ± 0.7 | 15.5 | 19.9 | 14.21 ± 2.42 |
| mattcl-py | input-pting | 16.7 ± 0.7 | 15.5 | 19.8 | 14.21 ± 2.42 |
| mattcl-py | input-chancalan | 16.7 ± 0.6 | 15.6 | 19.4 | 14.22 ± 2.41 |
| mattcl-py | input-kcen | 17.1 ± 4.3 | 15.8 | 58.7 | 14.55 ± 4.37 |
| pting | input-chancalan | 17.2 ± 0.7 | 16.0 | 20.2 | 14.63 ± 2.48 |
| pting | input-kcen | 17.2 ± 0.7 | 16.3 | 20.4 | 14.65 ± 2.49 |
| pting | input-mattcl | 17.2 ± 0.8 | 15.8 | 20.8 | 14.67 ± 2.51 |
| pting | input-pting | 17.2 ± 0.7 | 16.0 | 20.5 | 14.67 ± 2.51 |
| pting | input-lanjian | 17.4 ± 3.6 | 16.1 | 63.2 | 14.86 ± 3.91 |
| kcen | input-kcen | 20.5 ± 0.8 | 19.5 | 23.6 | 17.45 ± 2.96 |
| kcen | input-chancalan | 20.5 ± 0.8 | 19.5 | 24.3 | 17.45 ± 2.97 |
| kcen | input-mattcl | 20.5 ± 0.7 | 19.7 | 23.7 | 17.51 ± 2.96 |
| kcen | input-pting | 20.5 ± 0.7 | 19.6 | 23.2 | 17.52 ± 2.95 |
| kcen | input-lanjian | 20.5 ± 0.8 | 19.3 | 23.2 | 17.53 ± 2.97 |
| chancalan | input-kcen | 24.5 ± 0.6 | 23.5 | 27.1 | 20.90 ± 3.50 |
| chancalan | input-chancalan | 24.5 ± 0.8 | 23.5 | 27.4 | 20.91 ± 3.52 |
| chancalan | input-mattcl | 24.5 ± 0.8 | 23.3 | 28.1 | 20.93 ± 3.52 |
| chancalan | input-lanjian | 24.6 ± 0.9 | 23.3 | 27.6 | 20.95 ± 3.54 |
| chancalan | input-pting | 24.6 ± 0.8 | 23.2 | 27.3 | 21.01 ± 3.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|