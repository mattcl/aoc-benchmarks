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
| lanjian | input-kcen | 1.0 ± 0.2 | 0.3 | 1.2 | 1.00 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.29 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.3 | 1.02 ± 0.29 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.4 | 1.3 | 1.02 ± 0.28 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.3 | 1.02 ± 0.28 |
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.28 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.2 | 1.04 ± 0.27 |
| mattcl | input-aspidites | 1.1 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.29 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.6 | 1.6 | 1.06 ± 0.27 |
| mattcl | input-kcen | 1.1 ± 0.1 | 0.6 | 1.3 | 1.07 ± 0.26 |
| mattcl-ts | input-mattcl | 12.3 ± 0.4 | 11.1 | 13.2 | 12.17 ± 2.59 |
| mattcl-ts | input-kcen | 12.4 ± 0.4 | 11.3 | 13.4 | 12.20 ± 2.60 |
| mattcl-ts | input-lanjian | 12.4 ± 0.4 | 11.3 | 13.5 | 12.21 ± 2.60 |
| mattcl-ts | input-aspidites | 12.4 ± 0.4 | 11.2 | 13.5 | 12.23 ± 2.60 |
| mattcl-ts | input-chancalan | 12.4 ± 0.4 | 11.5 | 13.1 | 12.24 ± 2.60 |
| mikofo | input-mattcl | 12.5 ± 0.4 | 11.5 | 13.6 | 12.37 ± 2.63 |
| mikofo | input-chancalan | 12.6 ± 0.3 | 11.7 | 13.3 | 12.41 ± 2.63 |
| mikofo | input-kcen | 12.6 ± 0.3 | 11.8 | 13.4 | 12.41 ± 2.63 |
| mikofo | input-aspidites | 12.6 ± 0.3 | 11.5 | 13.5 | 12.42 ± 2.63 |
| mikofo | input-lanjian | 12.6 ± 0.3 | 11.7 | 13.5 | 12.42 ± 2.63 |
| aspidites | input-lanjian | 12.7 ± 0.4 | 11.6 | 14.1 | 12.51 ± 2.67 |
| aspidites | input-mattcl | 12.7 ± 0.5 | 11.8 | 14.4 | 12.51 ± 2.67 |
| aspidites | input-chancalan | 12.7 ± 0.5 | 11.7 | 14.1 | 12.53 ± 2.68 |
| aspidites | input-kcen | 12.7 ± 0.4 | 11.9 | 14.2 | 12.56 ± 2.67 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.8 | 15.2 | 12.62 ± 2.70 |
| pting | input-kcen | 15.4 ± 0.5 | 14.6 | 18.8 | 15.17 ± 3.23 |
| pting | input-chancalan | 15.4 ± 0.6 | 14.4 | 18.3 | 15.20 ± 3.25 |
| pting | input-lanjian | 15.4 ± 0.6 | 14.5 | 18.9 | 15.21 ± 3.26 |
| pting | input-aspidites | 15.4 ± 0.6 | 14.3 | 18.1 | 15.21 ± 3.25 |
| pting | input-mattcl | 15.4 ± 0.6 | 14.4 | 18.4 | 15.22 ± 3.25 |
| chancalan | input-aspidites | 15.6 ± 0.6 | 14.7 | 18.8 | 15.44 ± 3.30 |
| chancalan | input-lanjian | 15.7 ± 0.7 | 14.6 | 19.5 | 15.47 ± 3.32 |
| chancalan | input-chancalan | 15.7 ± 0.7 | 14.9 | 18.6 | 15.49 ± 3.32 |
| mattcl-py | input-lanjian | 15.7 ± 0.7 | 14.9 | 18.8 | 15.51 ± 3.33 |
| mattcl-py | input-chancalan | 15.7 ± 0.6 | 14.9 | 18.3 | 15.53 ± 3.31 |
| mattcl-py | input-mattcl | 15.7 ± 0.7 | 14.7 | 19.5 | 15.54 ± 3.34 |
| chancalan | input-mattcl | 15.7 ± 0.8 | 14.7 | 18.6 | 15.55 ± 3.36 |
| chancalan | input-kcen | 15.8 ± 0.7 | 14.8 | 18.7 | 15.56 ± 3.34 |
| mattcl-py | input-aspidites | 15.8 ± 0.7 | 14.9 | 19.1 | 15.63 ± 3.36 |
| mattcl-py | input-kcen | 15.9 ± 1.7 | 14.7 | 37.5 | 15.67 ± 3.70 |
| kcen | input-chancalan | 16.3 ± 0.6 | 15.2 | 19.8 | 16.07 ± 3.44 |
| kcen | input-aspidites | 16.3 ± 0.6 | 15.2 | 19.6 | 16.09 ± 3.44 |
| kcen | input-lanjian | 16.4 ± 0.8 | 15.1 | 19.8 | 16.16 ± 3.48 |
| kcen | input-mattcl | 16.4 ± 0.7 | 15.1 | 19.6 | 16.24 ± 3.48 |
| kcen | input-kcen | 16.6 ± 3.2 | 15.2 | 59.4 | 16.39 ± 4.69 |


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