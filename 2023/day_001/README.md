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
| lanjian | input-mattcl | 0.7 ± 0.3 | 0.2 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.6 | 1.35 ± 0.64 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.7 | 1.35 ± 0.64 |
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.8 | 1.39 ± 0.65 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.5 | 1.6 | 1.40 ± 0.64 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.3 | 1.6 | 1.41 ± 0.66 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.4 | 1.2 | 1.42 ± 0.64 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.6 | 1.44 ± 0.65 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.5 | 1.8 | 1.48 ± 0.67 |
| mattcl | input-kcen | 1.1 ± 0.1 | 0.6 | 1.6 | 1.50 ± 0.66 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.5 | 13.7 | 16.96 ± 7.19 |
| mattcl-ts | input-lanjian | 12.6 ± 0.3 | 11.7 | 13.4 | 16.97 ± 7.20 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.8 | 13.5 | 17.02 ± 7.21 |
| mattcl-ts | input-chancalan | 12.6 ± 0.3 | 11.8 | 13.4 | 17.03 ± 7.21 |
| aspidites | input-aspidites | 12.7 ± 0.5 | 11.6 | 14.1 | 17.08 ± 7.26 |
| aspidites | input-kcen | 12.7 ± 0.5 | 11.9 | 14.0 | 17.09 ± 7.26 |
| aspidites | input-lanjian | 12.8 ± 0.5 | 11.7 | 14.3 | 17.27 ± 7.34 |
| mikofo | input-kcen | 12.8 ± 0.3 | 11.7 | 13.7 | 17.30 ± 7.34 |
| aspidites | input-mattcl | 12.8 ± 0.5 | 11.8 | 14.3 | 17.31 ± 7.35 |
| mikofo | input-aspidites | 12.9 ± 0.4 | 11.9 | 14.5 | 17.34 ± 7.36 |
| mikofo | input-lanjian | 12.9 ± 0.4 | 11.8 | 13.8 | 17.35 ± 7.36 |
| mikofo | input-chancalan | 12.9 ± 0.3 | 12.1 | 13.7 | 17.38 ± 7.37 |
| aspidites | input-chancalan | 13.0 ± 2.9 | 11.1 | 52.4 | 17.48 ± 8.34 |
| mikofo | input-mattcl | 13.5 ± 5.3 | 11.9 | 71.9 | 18.20 ± 10.51 |
| mattcl-ts | input-aspidites | 13.8 ± 6.4 | 11.7 | 56.4 | 18.60 ± 11.66 |
| pting | input-lanjian | 15.6 ± 0.5 | 14.3 | 18.4 | 21.08 ± 8.95 |
| pting | input-mattcl | 15.7 ± 0.9 | 14.4 | 24.1 | 21.17 ± 9.04 |
| pting | input-chancalan | 15.8 ± 0.8 | 14.6 | 19.1 | 21.25 ± 9.05 |
| pting | input-kcen | 15.8 ± 0.7 | 14.7 | 18.5 | 21.29 ± 9.06 |
| chancalan | input-lanjian | 15.8 ± 0.6 | 15.0 | 19.0 | 21.36 ± 9.08 |
| mattcl-py | input-aspidites | 15.9 ± 0.5 | 14.6 | 18.3 | 21.46 ± 9.11 |
| chancalan | input-aspidites | 15.9 ± 0.8 | 14.6 | 18.8 | 21.50 ± 9.16 |
| mattcl-py | input-kcen | 16.0 ± 0.7 | 14.8 | 18.7 | 21.54 ± 9.16 |
| mattcl-py | input-lanjian | 16.0 ± 0.8 | 14.9 | 19.1 | 21.55 ± 9.17 |
| chancalan | input-mattcl | 16.0 ± 0.6 | 14.9 | 18.7 | 21.55 ± 9.16 |
| mattcl-py | input-chancalan | 16.0 ± 0.6 | 14.8 | 19.7 | 21.57 ± 9.17 |
| chancalan | input-chancalan | 16.0 ± 0.8 | 14.9 | 19.9 | 21.59 ± 9.20 |
| chancalan | input-kcen | 16.0 ± 0.6 | 14.6 | 18.7 | 21.61 ± 9.18 |
| mattcl-py | input-mattcl | 16.4 ± 2.7 | 14.6 | 46.8 | 22.06 ± 10.00 |
| kcen | input-lanjian | 16.4 ± 0.6 | 15.2 | 19.6 | 22.08 ± 9.38 |
| kcen | input-chancalan | 16.4 ± 0.6 | 15.4 | 19.4 | 22.14 ± 9.40 |
| kcen | input-kcen | 16.5 ± 0.6 | 15.5 | 19.6 | 22.19 ± 9.42 |
| kcen | input-mattcl | 16.5 ± 0.7 | 15.7 | 19.4 | 22.28 ± 9.47 |
| kcen | input-aspidites | 16.5 ± 0.7 | 15.4 | 19.6 | 22.30 ± 9.48 |
| pting | input-aspidites | 16.7 ± 6.9 | 14.6 | 69.1 | 22.52 ± 13.34 |


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