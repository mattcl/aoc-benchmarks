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
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.2 | 1.00 ± 0.29 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.6 | 1.01 ± 0.28 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.6 | 1.02 ± 0.29 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.28 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.6 | 1.03 ± 0.28 |
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.3 | 1.9 | 1.04 ± 0.30 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.4 | 1.7 | 1.04 ± 0.29 |
| lanjian | input-kcen | 1.0 ± 0.1 | 0.5 | 1.6 | 1.06 ± 0.26 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.5 | 1.7 | 1.07 ± 0.28 |
| aspidites | input-aspidites | 12.4 ± 1.6 | 10.5 | 28.0 | 12.82 ± 3.15 |
| mattcl-ts | input-kcen | 12.5 ± 0.3 | 11.6 | 13.8 | 12.92 ± 2.73 |
| mattcl-ts | input-aspidites | 12.6 ± 0.3 | 11.8 | 13.5 | 12.93 ± 2.73 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.8 | 13.6 | 12.93 ± 2.73 |
| mattcl-ts | input-chancalan | 12.6 ± 0.3 | 11.8 | 13.8 | 12.94 ± 2.73 |
| aspidites | input-kcen | 12.7 ± 0.5 | 11.4 | 14.1 | 13.06 ± 2.78 |
| aspidites | input-chancalan | 12.7 ± 0.4 | 11.8 | 14.0 | 13.08 ± 2.78 |
| aspidites | input-mattcl | 12.7 ± 0.5 | 11.4 | 14.0 | 13.09 ± 2.79 |
| aspidites | input-lanjian | 12.8 ± 0.5 | 11.7 | 14.3 | 13.14 ± 2.80 |
| mikofo | input-kcen | 12.8 ± 0.4 | 11.6 | 14.1 | 13.16 ± 2.78 |
| mikofo | input-mattcl | 12.8 ± 0.3 | 12.0 | 13.7 | 13.17 ± 2.78 |
| mikofo | input-lanjian | 12.8 ± 0.3 | 12.1 | 14.2 | 13.18 ± 2.78 |
| mikofo | input-chancalan | 12.8 ± 0.3 | 11.9 | 13.6 | 13.23 ± 2.79 |
| mikofo | input-aspidites | 12.9 ± 0.3 | 12.1 | 13.7 | 13.29 ± 2.81 |
| mattcl-ts | input-lanjian | 12.9 ± 3.9 | 11.6 | 55.9 | 13.34 ± 4.89 |
| pting | input-aspidites | 15.6 ± 0.6 | 14.3 | 18.8 | 16.06 ± 3.43 |
| pting | input-lanjian | 15.6 ± 0.6 | 14.6 | 18.5 | 16.09 ± 3.43 |
| pting | input-mattcl | 15.7 ± 0.6 | 14.7 | 18.4 | 16.13 ± 3.44 |
| pting | input-chancalan | 15.8 ± 0.7 | 14.6 | 18.6 | 16.23 ± 3.48 |
| mattcl-py | input-lanjian | 15.8 ± 0.9 | 14.6 | 22.6 | 16.31 ± 3.53 |
| mattcl-py | input-mattcl | 15.9 ± 0.6 | 14.7 | 18.2 | 16.34 ± 3.48 |
| mattcl-py | input-kcen | 15.9 ± 0.8 | 14.5 | 19.0 | 16.37 ± 3.53 |
| chancalan | input-kcen | 15.9 ± 0.6 | 14.8 | 18.7 | 16.38 ± 3.50 |
| pting | input-kcen | 15.9 ± 2.5 | 14.6 | 48.1 | 16.38 ± 4.29 |
| chancalan | input-mattcl | 15.9 ± 0.7 | 14.5 | 19.6 | 16.38 ± 3.51 |
| mattcl-py | input-aspidites | 15.9 ± 0.7 | 14.7 | 19.3 | 16.39 ± 3.50 |
| chancalan | input-chancalan | 15.9 ± 0.6 | 14.5 | 18.2 | 16.40 ± 3.49 |
| mattcl-py | input-chancalan | 16.0 ± 0.9 | 14.8 | 19.8 | 16.46 ± 3.57 |
| chancalan | input-aspidites | 16.1 ± 1.7 | 14.9 | 36.9 | 16.54 ± 3.87 |
| chancalan | input-lanjian | 16.2 ± 3.8 | 14.7 | 65.9 | 16.68 ± 5.21 |
| kcen | input-lanjian | 16.4 ± 0.6 | 15.5 | 19.4 | 16.88 ± 3.59 |
| kcen | input-mattcl | 16.4 ± 0.7 | 15.4 | 19.4 | 16.92 ± 3.62 |
| kcen | input-kcen | 16.4 ± 0.7 | 15.1 | 19.5 | 16.94 ± 3.63 |
| kcen | input-chancalan | 16.6 ± 0.6 | 15.7 | 19.6 | 17.07 ± 3.63 |
| kcen | input-aspidites | 16.6 ± 2.4 | 15.3 | 47.0 | 17.12 ± 4.37 |


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