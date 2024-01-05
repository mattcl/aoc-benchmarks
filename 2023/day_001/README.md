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
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.6 | 1.00 |
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.5 | 1.01 ± 0.25 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.5 | 1.01 ± 0.27 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.8 | 1.01 ± 0.27 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.6 | 1.02 ± 0.25 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.25 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.4 | 1.7 | 1.03 ± 0.25 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.7 | 1.04 ± 0.28 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.6 | 1.05 ± 0.26 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.7 | 1.05 ± 0.26 |
| mattcl-ts | input-aspidites | 12.5 ± 0.3 | 11.5 | 13.2 | 12.58 ± 2.38 |
| mattcl-ts | input-chancalan | 12.5 ± 0.3 | 11.6 | 13.4 | 12.59 ± 2.38 |
| mattcl-ts | input-lanjian | 12.5 ± 0.3 | 11.5 | 13.9 | 12.62 ± 2.39 |
| mikofo | input-lanjian | 12.7 ± 0.3 | 11.8 | 13.6 | 12.74 ± 2.41 |
| mikofo | input-mattcl | 12.7 ± 0.3 | 11.5 | 13.7 | 12.74 ± 2.41 |
| aspidites | input-lanjian | 12.7 ± 0.5 | 11.8 | 15.3 | 12.78 ± 2.45 |
| aspidites | input-chancalan | 12.7 ± 0.5 | 11.6 | 14.0 | 12.79 ± 2.45 |
| mikofo | input-chancalan | 12.7 ± 0.3 | 11.8 | 14.3 | 12.80 ± 2.42 |
| aspidites | input-mattcl | 12.7 ± 0.5 | 11.7 | 14.5 | 12.80 ± 2.45 |
| mikofo | input-aspidites | 12.7 ± 0.3 | 11.8 | 14.3 | 12.82 ± 2.42 |
| mattcl-ts | input-mattcl | 12.7 ± 2.9 | 11.8 | 53.3 | 12.83 ± 3.78 |
| aspidites | input-aspidites | 12.7 ± 0.5 | 11.6 | 14.3 | 12.83 ± 2.46 |
| aspidites | input-kcen | 12.8 ± 0.5 | 11.7 | 14.3 | 12.86 ± 2.45 |
| mattcl-ts | input-kcen | 12.8 ± 3.9 | 11.7 | 67.2 | 12.90 ± 4.59 |
| mikofo | input-kcen | 13.1 ± 4.5 | 11.6 | 70.6 | 13.17 ± 5.16 |
| pting | input-mattcl | 15.4 ± 0.6 | 14.6 | 19.2 | 15.52 ± 2.98 |
| pting | input-lanjian | 15.4 ± 0.6 | 14.5 | 18.3 | 15.54 ± 2.97 |
| pting | input-chancalan | 15.5 ± 0.6 | 14.6 | 18.9 | 15.56 ± 2.97 |
| pting | input-aspidites | 15.5 ± 0.7 | 14.4 | 18.4 | 15.56 ± 2.99 |
| pting | input-kcen | 15.5 ± 0.7 | 14.8 | 19.1 | 15.65 ± 3.01 |
| chancalan | input-mattcl | 15.6 ± 0.5 | 14.6 | 18.5 | 15.74 ± 3.00 |
| chancalan | input-kcen | 15.7 ± 0.5 | 14.7 | 18.5 | 15.77 ± 3.00 |
| mattcl-py | input-kcen | 15.7 ± 0.7 | 14.5 | 18.5 | 15.83 ± 3.04 |
| chancalan | input-chancalan | 15.7 ± 0.6 | 14.6 | 18.6 | 15.85 ± 3.04 |
| mattcl-py | input-lanjian | 15.8 ± 0.7 | 14.6 | 18.3 | 15.86 ± 3.05 |
| chancalan | input-aspidites | 15.8 ± 0.7 | 14.6 | 18.6 | 15.89 ± 3.06 |
| mattcl-py | input-mattcl | 15.8 ± 0.7 | 14.8 | 19.3 | 15.90 ± 3.07 |
| chancalan | input-lanjian | 15.8 ± 0.8 | 14.7 | 18.9 | 15.92 ± 3.09 |
| mattcl-py | input-chancalan | 15.8 ± 0.7 | 14.9 | 19.0 | 15.94 ± 3.08 |
| mattcl-py | input-aspidites | 15.9 ± 0.8 | 14.7 | 18.8 | 16.00 ± 3.11 |
| kcen | input-mattcl | 16.3 ± 0.7 | 15.1 | 19.6 | 16.42 ± 3.15 |
| kcen | input-lanjian | 16.3 ± 0.6 | 15.5 | 19.3 | 16.44 ± 3.14 |
| kcen | input-kcen | 16.3 ± 0.7 | 15.4 | 19.5 | 16.45 ± 3.15 |
| kcen | input-aspidites | 16.4 ± 0.7 | 15.5 | 19.4 | 16.51 ± 3.18 |
| kcen | input-chancalan | 16.5 ± 2.4 | 15.1 | 48.0 | 16.61 ± 3.96 |


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