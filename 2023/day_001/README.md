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
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.7 | 1.00 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.6 | 1.05 ± 0.31 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 2.0 | 1.05 ± 0.34 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.5 | 1.5 | 1.06 ± 0.30 |
| mattcl | input-aspidites | 1.1 ± 0.2 | 0.5 | 1.6 | 1.07 ± 0.31 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.5 | 1.07 ± 0.32 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.07 ± 0.32 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.4 | 1.8 | 1.08 ± 0.32 |
| lanjian | input-mikofo | 1.1 ± 0.2 | 0.5 | 1.7 | 1.08 ± 0.30 |
| lanjian | input-aspidites | 1.1 ± 0.2 | 0.2 | 1.6 | 1.08 ± 0.32 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.3 | 1.10 ± 0.30 |
| mattcl | input-mikofo | 1.1 ± 0.2 | 0.3 | 1.8 | 1.10 ± 0.32 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.5 | 1.10 ± 0.31 |
| lanjian | input-lanjian | 1.1 ± 0.1 | 0.5 | 1.6 | 1.10 ± 0.30 |
| mattcl-ts | input-mikofo | 12.7 ± 0.3 | 11.8 | 13.8 | 12.59 ± 3.03 |
| mattcl-ts | input-kcen | 12.7 ± 0.3 | 11.9 | 13.8 | 12.61 ± 3.03 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 12.0 | 14.1 | 12.61 ± 3.03 |
| mattcl-ts | input-lanjian | 12.7 ± 0.3 | 11.7 | 13.9 | 12.62 ± 3.04 |
| mattcl-ts | input-mattcl | 12.7 ± 0.3 | 12.1 | 13.7 | 12.62 ± 3.03 |
| mattcl-ts | input-pting | 12.7 ± 0.3 | 12.0 | 13.6 | 12.62 ± 3.04 |
| aspidites | input-pting | 12.8 ± 0.5 | 11.6 | 14.3 | 12.68 ± 3.07 |
| aspidites | input-chancalan | 12.8 ± 0.5 | 11.8 | 14.4 | 12.72 ± 3.08 |
| aspidites | input-lanjian | 12.8 ± 0.5 | 11.8 | 14.1 | 12.74 ± 3.09 |
| mikofo | input-kcen | 12.8 ± 0.3 | 11.8 | 13.8 | 12.77 ± 3.07 |
| aspidites | input-mattcl | 12.8 ± 0.5 | 11.5 | 14.3 | 12.77 ± 3.10 |
| aspidites | input-aspidites | 12.9 ± 0.5 | 11.9 | 14.4 | 12.78 ± 3.10 |
| aspidites | input-mikofo | 12.9 ± 0.5 | 11.7 | 14.3 | 12.80 ± 3.11 |
| aspidites | input-kcen | 12.9 ± 0.5 | 11.7 | 14.4 | 12.80 ± 3.10 |
| mikofo | input-lanjian | 12.9 ± 0.4 | 12.0 | 14.7 | 12.82 ± 3.09 |
| mikofo | input-chancalan | 12.9 ± 0.3 | 12.2 | 14.6 | 12.85 ± 3.09 |
| mikofo | input-aspidites | 13.0 ± 0.4 | 12.1 | 14.0 | 12.88 ± 3.10 |
| mikofo | input-mikofo | 13.0 ± 0.3 | 12.0 | 14.0 | 12.89 ± 3.10 |
| mikofo | input-mattcl | 13.0 ± 0.3 | 11.8 | 13.9 | 12.90 ± 3.11 |
| mikofo | input-pting | 13.0 ± 0.3 | 12.2 | 14.5 | 12.91 ± 3.11 |
| mattcl-ts | input-aspidites | 13.2 ± 4.9 | 11.8 | 74.2 | 13.07 ± 5.83 |
| pting | input-kcen | 15.8 ± 0.7 | 14.7 | 18.8 | 15.67 ± 3.81 |
| pting | input-aspidites | 15.8 ± 0.7 | 14.7 | 19.0 | 15.69 ± 3.81 |
| pting | input-chancalan | 15.8 ± 0.7 | 14.8 | 18.7 | 15.75 ± 3.84 |
| pting | input-mikofo | 15.9 ± 0.7 | 14.7 | 18.6 | 15.76 ± 3.84 |
| pting | input-pting | 15.9 ± 0.6 | 14.9 | 19.2 | 15.77 ± 3.83 |
| pting | input-mattcl | 15.9 ± 0.7 | 14.8 | 18.3 | 15.81 ± 3.85 |
| chancalan | input-pting | 16.0 ± 0.5 | 14.9 | 19.0 | 15.86 ± 3.83 |
| mattcl-py | input-lanjian | 16.0 ± 0.6 | 14.7 | 18.8 | 15.86 ± 3.84 |
| chancalan | input-lanjian | 16.0 ± 0.6 | 15.0 | 18.6 | 15.88 ± 3.85 |
| mattcl-py | input-chancalan | 16.0 ± 0.7 | 14.9 | 19.1 | 15.90 ± 3.87 |
| mattcl-py | input-aspidites | 16.0 ± 0.7 | 14.9 | 18.8 | 15.95 ± 3.88 |
| mattcl-py | input-kcen | 16.0 ± 0.7 | 15.0 | 19.3 | 15.95 ± 3.88 |
| mattcl-py | input-pting | 16.1 ± 0.6 | 15.0 | 18.6 | 15.96 ± 3.86 |
| chancalan | input-aspidites | 16.1 ± 0.6 | 14.9 | 18.5 | 15.96 ± 3.86 |
| pting | input-lanjian | 16.1 ± 3.7 | 14.4 | 61.5 | 15.99 ± 5.29 |
| chancalan | input-mikofo | 16.1 ± 0.7 | 14.9 | 20.4 | 15.99 ± 3.89 |
| mattcl-py | input-mattcl | 16.1 ± 0.7 | 14.7 | 19.4 | 16.01 ± 3.89 |
| chancalan | input-chancalan | 16.1 ± 0.7 | 15.1 | 18.7 | 16.02 ± 3.89 |
| chancalan | input-mattcl | 16.2 ± 0.8 | 14.8 | 19.5 | 16.06 ± 3.93 |
| mattcl-py | input-mikofo | 16.3 ± 2.8 | 14.7 | 53.1 | 16.25 ± 4.78 |
| chancalan | input-kcen | 16.4 ± 4.0 | 14.9 | 69.6 | 16.30 ± 5.56 |
| kcen | input-pting | 16.5 ± 0.6 | 15.4 | 19.3 | 16.41 ± 3.97 |
| kcen | input-mikofo | 16.5 ± 0.5 | 15.3 | 19.6 | 16.42 ± 3.96 |
| kcen | input-lanjian | 16.6 ± 0.6 | 15.5 | 19.7 | 16.48 ± 3.99 |
| kcen | input-chancalan | 16.6 ± 0.7 | 15.4 | 19.6 | 16.51 ± 4.02 |
| kcen | input-aspidites | 16.6 ± 0.7 | 15.2 | 19.9 | 16.53 ± 4.02 |
| kcen | input-mattcl | 16.7 ± 0.8 | 15.4 | 20.2 | 16.55 ± 4.04 |
| kcen | input-kcen | 16.7 ± 0.7 | 15.3 | 18.9 | 16.55 ± 4.01 |


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