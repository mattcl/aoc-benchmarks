# Day 1 benchmarks

[link to problem](https://adventofcode.com/2023/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [aspidites](https://github.com/aspidites/aoc2023) (haskell)
- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [mikofo](https://github.com/mikofo/advent-of-code-2023) (javascript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.6 | 1.00 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.2 | 1.6 | 1.00 ± 0.26 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.6 | 1.00 ± 0.29 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.7 | 1.01 ± 0.27 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.26 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.6 | 1.03 ± 0.28 |
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.26 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.4 | 1.6 | 1.04 ± 0.28 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.2 | 1.7 | 1.05 ± 0.27 |
| lanjian | input-lanjian | 1.1 ± 3.7 | 0.1 | 53.6 | 1.06 ± 3.73 |
| mattcl-ts | input-lanjian | 12.6 ± 0.3 | 11.8 | 13.5 | 12.52 ± 2.49 |
| mattcl-ts | input-chancalan | 12.6 ± 0.3 | 11.7 | 13.5 | 12.53 ± 2.50 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.8 | 13.6 | 12.55 ± 2.50 |
| mattcl-ts | input-aspidites | 12.6 ± 0.3 | 11.5 | 14.2 | 12.55 ± 2.51 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.7 | 13.8 | 12.58 ± 2.51 |
| aspidites | input-chancalan | 12.7 ± 0.5 | 11.6 | 14.6 | 12.59 ± 2.53 |
| aspidites | input-kcen | 12.7 ± 0.5 | 11.5 | 14.2 | 12.60 ± 2.55 |
| aspidites | input-lanjian | 12.7 ± 0.5 | 11.3 | 14.5 | 12.64 ± 2.56 |
| aspidites | input-mattcl | 12.8 ± 0.5 | 11.5 | 14.1 | 12.71 ± 2.56 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.8 | 14.8 | 12.74 ± 2.57 |
| mikofo | input-lanjian | 12.8 ± 0.3 | 11.9 | 13.6 | 12.76 ± 2.55 |
| mikofo | input-aspidites | 12.9 ± 0.4 | 11.9 | 13.9 | 12.79 ± 2.56 |
| mikofo | input-chancalan | 12.9 ± 0.4 | 11.8 | 13.7 | 12.81 ± 2.56 |
| mikofo | input-mattcl | 12.9 ± 0.3 | 12.0 | 13.7 | 12.81 ± 2.56 |
| mikofo | input-kcen | 13.9 ± 6.6 | 11.8 | 67.5 | 13.83 ± 7.15 |
| pting | input-mattcl | 15.7 ± 0.8 | 14.4 | 18.9 | 15.66 ± 3.19 |
| pting | input-aspidites | 15.8 ± 0.8 | 14.7 | 18.6 | 15.71 ± 3.20 |
| pting | input-chancalan | 15.8 ± 0.7 | 14.4 | 19.5 | 15.72 ± 3.20 |
| pting | input-kcen | 15.8 ± 0.8 | 14.4 | 19.0 | 15.74 ± 3.22 |
| pting | input-lanjian | 15.8 ± 0.7 | 14.5 | 19.4 | 15.75 ± 3.20 |
| chancalan | input-aspidites | 15.9 ± 0.6 | 14.7 | 19.1 | 15.83 ± 3.20 |
| mattcl-py | input-mattcl | 15.9 ± 0.6 | 14.8 | 18.5 | 15.87 ± 3.20 |
| mattcl-py | input-chancalan | 16.0 ± 0.5 | 14.9 | 18.8 | 15.91 ± 3.19 |
| mattcl-py | input-kcen | 16.0 ± 0.7 | 14.6 | 18.7 | 15.92 ± 3.22 |
| chancalan | input-chancalan | 16.0 ± 0.8 | 15.0 | 19.1 | 15.93 ± 3.24 |
| chancalan | input-kcen | 16.0 ± 0.7 | 14.6 | 19.0 | 15.94 ± 3.24 |
| mattcl-py | input-aspidites | 16.0 ± 0.7 | 15.0 | 20.2 | 15.94 ± 3.23 |
| chancalan | input-mattcl | 16.1 ± 0.7 | 15.1 | 19.5 | 15.97 ± 3.24 |
| mattcl-py | input-lanjian | 16.1 ± 0.6 | 14.9 | 19.6 | 15.97 ± 3.22 |
| chancalan | input-lanjian | 16.4 ± 4.7 | 15.1 | 78.5 | 16.32 ± 5.70 |
| kcen | input-mattcl | 16.4 ± 0.5 | 15.2 | 19.3 | 16.36 ± 3.27 |
| kcen | input-kcen | 16.5 ± 0.6 | 15.6 | 19.8 | 16.39 ± 3.30 |
| kcen | input-aspidites | 16.5 ± 0.7 | 15.2 | 19.8 | 16.40 ± 3.31 |
| kcen | input-lanjian | 16.6 ± 0.7 | 15.4 | 20.0 | 16.48 ± 3.33 |
| kcen | input-chancalan | 16.6 ± 0.8 | 15.3 | 20.3 | 16.56 ± 3.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-mikofo|<pre>55538</pre>|<pre>54875</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|