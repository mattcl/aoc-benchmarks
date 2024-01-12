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
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.8 | 1.01 ± 0.27 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.8 | 1.03 ± 0.24 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.26 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.4 | 1.9 | 1.04 ± 0.25 |
| lanjian | input-aspidites | 1.1 ± 0.2 | 0.6 | 1.8 | 1.04 ± 0.26 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.8 | 1.06 ± 0.24 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.9 | 1.06 ± 0.25 |
| mattcl | input-aspidites | 1.2 ± 0.2 | 0.6 | 1.9 | 1.08 ± 0.27 |
| lanjian | input-chancalan | 1.2 ± 0.1 | 0.6 | 1.7 | 1.09 ± 0.24 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 12.0 | 13.5 | 11.63 ± 2.21 |
| mattcl-ts | input-mattcl | 12.7 ± 0.3 | 11.8 | 13.6 | 11.64 ± 2.22 |
| mattcl-ts | input-kcen | 12.7 ± 0.3 | 11.7 | 14.0 | 11.65 ± 2.22 |
| mattcl-ts | input-lanjian | 12.7 ± 0.3 | 12.0 | 14.0 | 11.68 ± 2.22 |
| aspidites | input-lanjian | 12.8 ± 0.5 | 11.7 | 14.6 | 11.74 ± 2.27 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.8 | 14.2 | 11.75 ± 2.26 |
| aspidites | input-chancalan | 12.8 ± 0.4 | 11.9 | 14.1 | 11.78 ± 2.26 |
| aspidites | input-mattcl | 12.9 ± 0.5 | 11.9 | 14.5 | 11.82 ± 2.28 |
| mikofo | input-lanjian | 12.9 ± 0.4 | 12.0 | 13.8 | 11.86 ± 2.27 |
| aspidites | input-kcen | 12.9 ± 0.5 | 11.9 | 14.3 | 11.87 ± 2.29 |
| mikofo | input-kcen | 12.9 ± 0.3 | 12.1 | 14.0 | 11.87 ± 2.27 |
| mikofo | input-aspidites | 13.0 ± 0.4 | 12.2 | 14.2 | 11.90 ± 2.27 |
| mikofo | input-mattcl | 13.0 ± 0.4 | 12.0 | 14.7 | 11.91 ± 2.28 |
| mikofo | input-chancalan | 13.0 ± 0.4 | 11.9 | 14.3 | 11.91 ± 2.28 |
| mattcl-ts | input-aspidites | 13.4 ± 5.7 | 11.5 | 66.8 | 12.26 ± 5.76 |
| pting | input-lanjian | 15.7 ± 0.7 | 14.8 | 19.0 | 14.41 ± 2.79 |
| pting | input-mattcl | 15.8 ± 0.6 | 14.8 | 18.6 | 14.49 ± 2.79 |
| pting | input-chancalan | 15.8 ± 0.7 | 14.7 | 18.9 | 14.51 ± 2.81 |
| pting | input-aspidites | 15.8 ± 0.6 | 14.8 | 18.7 | 14.53 ± 2.80 |
| pting | input-kcen | 15.8 ± 0.8 | 14.4 | 19.4 | 14.53 ± 2.84 |
| mattcl-py | input-aspidites | 16.0 ± 0.5 | 14.9 | 18.6 | 14.66 ± 2.82 |
| chancalan | input-kcen | 16.0 ± 0.7 | 14.7 | 18.7 | 14.69 ± 2.84 |
| chancalan | input-mattcl | 16.0 ± 0.7 | 14.7 | 18.9 | 14.71 ± 2.85 |
| chancalan | input-chancalan | 16.0 ± 0.6 | 15.0 | 18.6 | 14.71 ± 2.84 |
| mattcl-py | input-kcen | 16.0 ± 0.6 | 15.0 | 19.7 | 14.71 ± 2.84 |
| chancalan | input-lanjian | 16.0 ± 0.8 | 14.7 | 19.0 | 14.71 ± 2.87 |
| chancalan | input-aspidites | 16.1 ± 0.7 | 15.0 | 19.8 | 14.74 ± 2.86 |
| mattcl-py | input-mattcl | 16.1 ± 0.6 | 14.8 | 19.4 | 14.77 ± 2.85 |
| mattcl-py | input-lanjian | 16.1 ± 0.6 | 15.1 | 18.5 | 14.77 ± 2.85 |
| mattcl-py | input-chancalan | 16.2 ± 0.7 | 15.1 | 18.7 | 14.83 ± 2.88 |
| kcen | input-chancalan | 16.5 ± 0.6 | 15.3 | 19.7 | 15.13 ± 2.92 |
| kcen | input-aspidites | 16.6 ± 0.5 | 15.9 | 20.3 | 15.18 ± 2.91 |
| kcen | input-kcen | 16.6 ± 0.6 | 15.6 | 19.6 | 15.23 ± 2.94 |
| kcen | input-lanjian | 16.6 ± 0.7 | 15.7 | 19.7 | 15.23 ± 2.96 |
| kcen | input-mattcl | 17.1 ± 3.0 | 15.5 | 42.8 | 15.65 ± 4.02 |


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