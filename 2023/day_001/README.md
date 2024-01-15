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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.4 | 1.5 | 1.03 ± 0.25 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.3 | 1.4 | 1.03 ± 0.27 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.5 | 1.2 | 1.04 ± 0.25 |
| lanjian | input-aspidites | 1.0 ± 0.1 | 0.5 | 1.2 | 1.04 ± 0.24 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.4 | 1.4 | 1.04 ± 0.25 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.7 | 1.05 ± 0.26 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.4 | 1.2 | 1.05 ± 0.25 |
| lanjian | input-chancalan | 1.0 ± 0.1 | 0.6 | 1.7 | 1.06 ± 0.24 |
| lanjian | input-lanjian | 1.1 ± 0.1 | 0.6 | 1.3 | 1.07 ± 0.23 |
| mikofo | input-lanjian | 11.8 ± 0.4 | 10.8 | 12.7 | 11.92 ± 2.29 |
| mikofo | input-mattcl | 11.9 ± 0.4 | 10.8 | 13.2 | 11.98 ± 2.31 |
| mattcl-ts | input-chancalan | 11.9 ± 0.5 | 10.8 | 13.2 | 11.99 ± 2.32 |
| mattcl-ts | input-lanjian | 11.9 ± 0.5 | 10.6 | 13.1 | 11.99 ± 2.32 |
| mikofo | input-chancalan | 11.9 ± 0.5 | 10.7 | 13.3 | 12.01 ± 2.32 |
| mikofo | input-aspidites | 11.9 ± 0.5 | 10.7 | 12.9 | 12.02 ± 2.32 |
| mikofo | input-kcen | 11.9 ± 0.4 | 10.8 | 12.9 | 12.03 ± 2.31 |
| mattcl-ts | input-mattcl | 11.9 ± 0.4 | 10.9 | 13.1 | 12.04 ± 2.32 |
| mattcl-ts | input-kcen | 12.0 ± 0.4 | 10.9 | 13.0 | 12.07 ± 2.33 |
| mattcl-ts | input-aspidites | 12.0 ± 0.4 | 10.9 | 13.2 | 12.09 ± 2.32 |
| aspidites | input-lanjian | 12.5 ± 0.4 | 11.3 | 14.2 | 12.58 ± 2.42 |
| aspidites | input-chancalan | 12.5 ± 0.4 | 11.6 | 13.8 | 12.65 ± 2.43 |
| aspidites | input-aspidites | 12.6 ± 0.4 | 11.6 | 13.8 | 12.71 ± 2.44 |
| aspidites | input-mattcl | 12.6 ± 0.4 | 11.7 | 13.8 | 12.72 ± 2.44 |
| aspidites | input-kcen | 12.6 ± 0.5 | 11.7 | 13.9 | 12.76 ± 2.46 |
| pting | input-lanjian | 15.3 ± 0.5 | 14.6 | 18.2 | 15.47 ± 2.97 |
| pting | input-kcen | 15.4 ± 0.6 | 14.6 | 18.5 | 15.52 ± 2.99 |
| pting | input-aspidites | 15.4 ± 0.6 | 14.6 | 18.4 | 15.58 ± 3.01 |
| pting | input-chancalan | 15.5 ± 0.7 | 14.5 | 18.9 | 15.60 ± 3.02 |
| pting | input-mattcl | 15.5 ± 0.7 | 14.6 | 18.8 | 15.60 ± 3.02 |
| chancalan | input-lanjian | 15.6 ± 0.5 | 14.7 | 18.4 | 15.73 ± 3.02 |
| chancalan | input-mattcl | 15.6 ± 0.6 | 14.5 | 19.0 | 15.78 ± 3.05 |
| chancalan | input-chancalan | 15.6 ± 0.6 | 14.6 | 19.1 | 15.79 ± 3.04 |
| mattcl-py | input-kcen | 15.6 ± 0.6 | 14.7 | 19.0 | 15.79 ± 3.05 |
| chancalan | input-kcen | 15.7 ± 0.6 | 14.7 | 19.2 | 15.83 ± 3.06 |
| chancalan | input-aspidites | 15.7 ± 0.7 | 15.0 | 18.5 | 15.87 ± 3.07 |
| mattcl-py | input-lanjian | 15.7 ± 0.7 | 14.9 | 19.4 | 15.88 ± 3.08 |
| mattcl-py | input-mattcl | 15.7 ± 0.6 | 15.0 | 18.4 | 15.90 ± 3.06 |
| mattcl-py | input-aspidites | 15.8 ± 0.7 | 14.8 | 19.5 | 15.90 ± 3.08 |
| mattcl-py | input-chancalan | 15.8 ± 0.6 | 14.8 | 18.1 | 15.94 ± 3.07 |
| kcen | input-aspidites | 16.3 ± 0.4 | 15.8 | 19.1 | 16.47 ± 3.15 |
| kcen | input-lanjian | 16.3 ± 0.7 | 15.1 | 19.8 | 16.47 ± 3.20 |
| kcen | input-kcen | 16.4 ± 0.7 | 15.1 | 19.6 | 16.52 ± 3.20 |
| kcen | input-chancalan | 16.4 ± 0.6 | 15.4 | 19.3 | 16.53 ± 3.19 |
| kcen | input-mattcl | 16.4 ± 0.8 | 15.1 | 19.3 | 16.54 ± 3.23 |


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