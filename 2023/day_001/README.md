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
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.5 | 1.8 | 1.00 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.8 | 1.01 ± 0.26 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.5 | 1.7 | 1.01 ± 0.22 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.24 |
| lanjian | input-aspidites | 1.1 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.24 |
| mattcl | input-aspidites | 1.1 ± 0.2 | 0.2 | 1.7 | 1.02 ± 0.23 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.7 | 1.02 ± 0.22 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.4 | 2.6 | 1.03 ± 0.25 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.6 | 1.04 ± 0.22 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.8 | 1.05 ± 0.26 |
| mattcl-ts | input-lanjian | 12.7 ± 0.3 | 11.9 | 13.7 | 11.58 ± 1.94 |
| mattcl-ts | input-mattcl | 12.7 ± 0.3 | 11.8 | 13.8 | 11.59 ± 1.95 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 12.0 | 13.8 | 11.60 ± 1.96 |
| aspidites | input-kcen | 12.7 ± 0.5 | 11.1 | 14.0 | 11.60 ± 1.98 |
| mattcl-ts | input-aspidites | 12.7 ± 0.3 | 11.7 | 13.8 | 11.60 ± 1.95 |
| mattcl-ts | input-kcen | 12.7 ± 0.3 | 11.9 | 13.4 | 11.63 ± 1.96 |
| aspidites | input-mattcl | 12.8 ± 0.6 | 11.8 | 15.0 | 11.70 ± 2.02 |
| aspidites | input-lanjian | 12.9 ± 0.5 | 11.6 | 14.4 | 11.75 ± 2.00 |
| aspidites | input-aspidites | 12.9 ± 0.5 | 11.8 | 14.2 | 11.75 ± 2.00 |
| aspidites | input-chancalan | 12.9 ± 0.5 | 11.8 | 14.1 | 11.76 ± 2.00 |
| mikofo | input-chancalan | 12.9 ± 0.3 | 12.1 | 13.8 | 11.79 ± 1.99 |
| mikofo | input-kcen | 12.9 ± 0.4 | 12.1 | 14.5 | 11.79 ± 1.99 |
| mikofo | input-mattcl | 12.9 ± 0.4 | 11.8 | 14.5 | 11.80 ± 1.99 |
| mikofo | input-lanjian | 12.9 ± 0.3 | 12.2 | 13.9 | 11.81 ± 1.99 |
| mikofo | input-aspidites | 13.0 ± 0.3 | 12.3 | 13.9 | 11.90 ± 2.00 |
| pting | input-aspidites | 15.8 ± 0.7 | 14.7 | 18.4 | 14.45 ± 2.48 |
| pting | input-lanjian | 15.8 ± 0.8 | 14.8 | 19.2 | 14.45 ± 2.51 |
| pting | input-kcen | 15.8 ± 0.6 | 14.7 | 19.0 | 14.47 ± 2.48 |
| pting | input-mattcl | 15.9 ± 0.7 | 14.7 | 18.6 | 14.49 ± 2.49 |
| pting | input-chancalan | 15.9 ± 0.7 | 14.6 | 18.9 | 14.49 ± 2.49 |
| chancalan | input-chancalan | 16.0 ± 0.6 | 14.7 | 18.2 | 14.62 ± 2.49 |
| chancalan | input-mattcl | 16.0 ± 0.8 | 14.9 | 19.0 | 14.64 ± 2.53 |
| mattcl-py | input-aspidites | 16.0 ± 0.5 | 14.9 | 18.6 | 14.65 ± 2.48 |
| chancalan | input-aspidites | 16.1 ± 0.7 | 14.7 | 19.0 | 14.66 ± 2.53 |
| mattcl-py | input-lanjian | 16.1 ± 0.6 | 14.8 | 19.4 | 14.67 ± 2.51 |
| mattcl-py | input-mattcl | 16.1 ± 0.7 | 15.1 | 19.3 | 14.71 ± 2.52 |
| chancalan | input-lanjian | 16.1 ± 2.3 | 14.8 | 45.5 | 14.72 ± 3.20 |
| chancalan | input-kcen | 16.1 ± 0.7 | 14.9 | 19.4 | 14.74 ± 2.54 |
| mattcl-py | input-chancalan | 16.2 ± 0.8 | 14.8 | 19.7 | 14.77 ± 2.57 |
| mattcl-py | input-kcen | 16.2 ± 2.1 | 14.8 | 43.3 | 14.79 ± 3.12 |
| kcen | input-mattcl | 16.5 ± 0.7 | 15.7 | 19.5 | 15.11 ± 2.59 |
| kcen | input-kcen | 16.6 ± 0.6 | 15.2 | 20.2 | 15.16 ± 2.59 |
| kcen | input-chancalan | 16.6 ± 0.6 | 15.7 | 19.2 | 15.16 ± 2.58 |
| kcen | input-aspidites | 16.7 ± 0.7 | 15.5 | 20.0 | 15.23 ± 2.62 |
| kcen | input-lanjian | 16.8 ± 2.5 | 15.4 | 48.0 | 15.34 ± 3.43 |


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