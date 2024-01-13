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
| lanjian | input-kcen | 1.1 ± 0.2 | 0.5 | 1.8 | 1.00 |
| mattcl | input-aspidites | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 ± 0.22 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.23 |
| lanjian | input-aspidites | 1.1 ± 0.2 | 0.6 | 1.8 | 1.01 ± 0.22 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.9 | 1.01 ± 0.22 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.7 | 1.02 ± 0.22 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.8 | 1.03 ± 0.22 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.7 | 1.03 ± 0.23 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 2.0 | 1.04 ± 0.23 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.3 | 2.0 | 1.04 ± 0.23 |
| mattcl-ts | input-aspidites | 12.7 ± 0.3 | 11.9 | 13.6 | 11.29 ± 1.75 |
| aspidites | input-lanjian | 12.7 ± 0.5 | 11.8 | 14.3 | 11.30 ± 1.79 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 11.9 | 13.8 | 11.31 ± 1.75 |
| mattcl-ts | input-lanjian | 12.7 ± 0.3 | 11.9 | 13.7 | 11.33 ± 1.75 |
| mattcl-ts | input-kcen | 12.7 ± 0.3 | 11.9 | 13.9 | 11.34 ± 1.75 |
| mattcl-ts | input-mattcl | 12.7 ± 0.3 | 12.1 | 14.4 | 11.34 ± 1.76 |
| aspidites | input-mattcl | 12.8 ± 0.5 | 11.7 | 14.5 | 11.40 ± 1.80 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.2 | 14.3 | 11.41 ± 1.80 |
| aspidites | input-chancalan | 12.9 ± 0.5 | 11.5 | 14.9 | 11.48 ± 1.82 |
| aspidites | input-kcen | 12.9 ± 0.5 | 11.9 | 14.3 | 11.52 ± 1.82 |
| mikofo | input-mattcl | 12.9 ± 0.3 | 12.0 | 14.0 | 11.53 ± 1.79 |
| mikofo | input-kcen | 13.0 ± 0.3 | 12.2 | 13.7 | 11.56 ± 1.79 |
| mikofo | input-lanjian | 13.0 ± 0.3 | 12.1 | 13.9 | 11.57 ± 1.80 |
| mikofo | input-aspidites | 13.0 ± 0.4 | 11.9 | 14.4 | 11.58 ± 1.81 |
| mikofo | input-chancalan | 13.0 ± 0.3 | 12.3 | 14.0 | 11.60 ± 1.80 |
| pting | input-chancalan | 15.7 ± 0.6 | 14.4 | 18.6 | 14.01 ± 2.22 |
| pting | input-kcen | 15.8 ± 0.6 | 14.8 | 18.7 | 14.05 ± 2.21 |
| pting | input-aspidites | 15.8 ± 0.6 | 14.7 | 19.3 | 14.07 ± 2.23 |
| pting | input-lanjian | 15.8 ± 0.7 | 14.7 | 19.3 | 14.12 ± 2.25 |
| pting | input-mattcl | 15.9 ± 0.8 | 15.0 | 18.8 | 14.19 ± 2.28 |
| mattcl-py | input-lanjian | 16.0 ± 0.6 | 14.9 | 18.6 | 14.22 ± 2.25 |
| chancalan | input-aspidites | 16.0 ± 0.5 | 15.2 | 18.9 | 14.23 ± 2.22 |
| mattcl-py | input-chancalan | 16.0 ± 0.6 | 14.8 | 18.2 | 14.25 ± 2.25 |
| chancalan | input-lanjian | 16.0 ± 0.6 | 15.0 | 18.6 | 14.28 ± 2.25 |
| chancalan | input-kcen | 16.0 ± 0.7 | 14.8 | 18.9 | 14.29 ± 2.27 |
| chancalan | input-chancalan | 16.0 ± 0.7 | 14.7 | 19.3 | 14.29 ± 2.28 |
| mattcl-py | input-mattcl | 16.1 ± 0.6 | 15.2 | 19.1 | 14.30 ± 2.25 |
| chancalan | input-mattcl | 16.1 ± 0.7 | 15.1 | 19.4 | 14.34 ± 2.28 |
| mattcl-py | input-aspidites | 16.1 ± 0.6 | 15.0 | 19.7 | 14.35 ± 2.26 |
| mattcl-py | input-kcen | 16.3 ± 2.4 | 14.8 | 46.4 | 14.54 ± 3.09 |
| kcen | input-lanjian | 16.5 ± 0.6 | 15.2 | 19.6 | 14.69 ± 2.32 |
| kcen | input-mattcl | 16.5 ± 0.6 | 15.5 | 19.4 | 14.73 ± 2.32 |
| kcen | input-chancalan | 16.6 ± 0.6 | 15.6 | 19.1 | 14.82 ± 2.33 |
| kcen | input-aspidites | 16.6 ± 0.6 | 15.6 | 19.9 | 14.83 ± 2.34 |
| kcen | input-kcen | 16.8 ± 4.2 | 15.3 | 71.9 | 15.00 ± 4.43 |


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