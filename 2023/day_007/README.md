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
| mattcl | input-pting | 1.3 ± 0.2 | 0.4 | 1.8 | 1.00 |
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.4 | 1.8 | 1.02 ± 0.23 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.8 | 1.02 ± 0.22 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.8 | 1.02 ± 0.21 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.9 | 1.03 ± 0.20 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.4 | 1.8 | 1.04 ± 0.21 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.4 | 1.8 | 1.06 ± 0.21 |
| lanjian | input-kcen | 1.3 ± 0.1 | 0.9 | 1.8 | 1.06 ± 0.18 |
| mattcl | input-kcen | 1.3 ± 0.1 | 0.8 | 1.8 | 1.07 ± 0.19 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.6 | 2.0 | 1.08 ± 0.25 |
| mattcl-ts | input-lanjian | 14.3 ± 0.4 | 13.2 | 15.3 | 11.36 ± 1.67 |
| mattcl-ts | input-kcen | 14.3 ± 0.4 | 13.3 | 15.3 | 11.37 ± 1.66 |
| mattcl-ts | input-mattcl | 14.3 ± 0.4 | 13.2 | 15.3 | 11.37 ± 1.67 |
| mattcl-ts | input-chancalan | 14.3 ± 0.4 | 13.5 | 15.6 | 11.39 ± 1.67 |
| mattcl-ts | input-pting | 14.3 ± 0.4 | 13.2 | 15.9 | 11.40 ± 1.67 |
| mattcl-py | input-lanjian | 16.7 ± 0.6 | 15.5 | 19.7 | 13.33 ± 1.97 |
| mattcl-py | input-pting | 16.7 ± 0.7 | 15.6 | 19.9 | 13.35 ± 1.99 |
| mattcl-py | input-mattcl | 16.8 ± 0.6 | 15.7 | 19.2 | 13.41 ± 1.98 |
| mattcl-py | input-chancalan | 16.8 ± 0.7 | 15.6 | 20.2 | 13.43 ± 2.00 |
| mattcl-py | input-kcen | 16.9 ± 0.6 | 15.7 | 20.4 | 13.45 ± 2.00 |
| pting | input-lanjian | 17.4 ± 0.7 | 16.3 | 21.2 | 13.88 ± 2.08 |
| pting | input-chancalan | 17.4 ± 0.7 | 16.6 | 20.4 | 13.89 ± 2.06 |
| pting | input-mattcl | 17.4 ± 0.6 | 16.5 | 20.5 | 13.91 ± 2.06 |
| pting | input-kcen | 17.5 ± 0.6 | 16.2 | 20.7 | 13.93 ± 2.06 |
| pting | input-pting | 17.6 ± 0.8 | 16.4 | 21.2 | 14.07 ± 2.13 |
| kcen | input-kcen | 20.5 ± 0.5 | 19.5 | 22.7 | 16.32 ± 2.38 |
| kcen | input-chancalan | 20.6 ± 0.7 | 19.3 | 23.7 | 16.44 ± 2.44 |
| kcen | input-lanjian | 20.6 ± 0.7 | 19.5 | 24.2 | 16.45 ± 2.43 |
| kcen | input-pting | 20.7 ± 0.7 | 19.6 | 23.0 | 16.52 ± 2.44 |
| kcen | input-mattcl | 20.7 ± 0.8 | 19.4 | 23.6 | 16.52 ± 2.47 |
| chancalan | input-lanjian | 24.7 ± 0.7 | 23.3 | 27.4 | 19.69 ± 2.88 |
| chancalan | input-kcen | 24.7 ± 0.7 | 23.5 | 27.1 | 19.71 ± 2.89 |
| chancalan | input-mattcl | 24.8 ± 0.8 | 23.5 | 27.6 | 19.75 ± 2.91 |
| chancalan | input-chancalan | 24.8 ± 1.0 | 22.9 | 28.0 | 19.75 ± 2.95 |
| chancalan | input-pting | 25.0 ± 0.9 | 22.9 | 27.5 | 19.90 ± 2.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|