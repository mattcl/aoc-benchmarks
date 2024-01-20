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
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.3 | 1.00 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.8 | 1.00 ± 0.23 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.3 | 1.9 | 1.01 ± 0.26 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.23 |
| lanjian | input-aspidites | 1.1 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.23 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.4 | 1.02 ± 0.22 |
| mattcl | input-aspidites | 1.1 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.24 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.22 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.8 | 1.03 ± 0.23 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.4 | 2.1 | 1.05 ± 0.24 |
| mattcl-ts | input-lanjian | 12.4 ± 0.4 | 11.4 | 13.3 | 11.63 ± 1.95 |
| mattcl-ts | input-aspidites | 12.4 ± 0.4 | 11.2 | 13.5 | 11.64 ± 1.95 |
| mattcl-ts | input-mattcl | 12.4 ± 0.4 | 11.3 | 13.2 | 11.65 ± 1.95 |
| mattcl-ts | input-chancalan | 12.4 ± 0.4 | 11.1 | 13.3 | 11.65 ± 1.95 |
| mikofo | input-lanjian | 12.4 ± 0.4 | 11.3 | 13.6 | 11.67 ± 1.96 |
| aspidites | input-mattcl | 12.4 ± 0.6 | 11.0 | 13.7 | 11.67 ± 2.01 |
| mikofo | input-kcen | 12.4 ± 0.4 | 11.6 | 13.6 | 11.68 ± 1.96 |
| mattcl-ts | input-kcen | 12.4 ± 0.3 | 11.4 | 13.3 | 11.69 ± 1.96 |
| mikofo | input-chancalan | 12.5 ± 0.4 | 11.3 | 13.4 | 11.70 ± 1.96 |
| mikofo | input-aspidites | 12.5 ± 0.4 | 11.5 | 14.1 | 11.72 ± 1.97 |
| mikofo | input-mattcl | 12.5 ± 0.3 | 11.6 | 13.3 | 11.75 ± 1.96 |
| aspidites | input-aspidites | 12.7 ± 0.5 | 11.6 | 14.1 | 11.88 ± 2.01 |
| aspidites | input-lanjian | 12.7 ± 0.5 | 11.8 | 14.3 | 11.96 ± 2.02 |
| aspidites | input-chancalan | 12.8 ± 0.4 | 11.9 | 13.9 | 12.02 ± 2.02 |
| aspidites | input-kcen | 12.8 ± 0.4 | 11.8 | 14.1 | 12.03 ± 2.03 |
| pting | input-kcen | 15.4 ± 0.4 | 14.6 | 17.1 | 14.51 ± 2.42 |
| pting | input-lanjian | 15.5 ± 0.6 | 14.6 | 18.5 | 14.55 ± 2.46 |
| pting | input-mattcl | 15.5 ± 0.7 | 14.6 | 18.6 | 14.57 ± 2.49 |
| pting | input-chancalan | 15.6 ± 0.7 | 14.6 | 18.7 | 14.64 ± 2.49 |
| pting | input-aspidites | 15.7 ± 0.7 | 14.9 | 19.1 | 14.73 ± 2.52 |
| mattcl-py | input-kcen | 15.8 ± 0.6 | 14.6 | 18.2 | 14.84 ± 2.50 |
| chancalan | input-lanjian | 15.8 ± 0.7 | 15.0 | 18.6 | 14.85 ± 2.53 |
| chancalan | input-mattcl | 15.8 ± 0.7 | 14.8 | 19.1 | 14.86 ± 2.53 |
| chancalan | input-chancalan | 15.8 ± 0.7 | 14.7 | 19.5 | 14.87 ± 2.53 |
| chancalan | input-kcen | 15.8 ± 0.6 | 14.8 | 18.6 | 14.87 ± 2.52 |
| mattcl-py | input-lanjian | 15.8 ± 0.7 | 14.9 | 19.4 | 14.88 ± 2.54 |
| mattcl-py | input-mattcl | 15.9 ± 0.7 | 14.6 | 18.4 | 14.89 ± 2.53 |
| mattcl-py | input-chancalan | 15.9 ± 0.7 | 15.0 | 18.8 | 14.90 ± 2.54 |
| mattcl-py | input-aspidites | 15.9 ± 0.6 | 14.9 | 19.2 | 14.91 ± 2.53 |
| chancalan | input-aspidites | 15.9 ± 0.7 | 15.0 | 18.8 | 14.92 ± 2.56 |
| kcen | input-mattcl | 16.4 ± 0.6 | 15.3 | 19.5 | 15.38 ± 2.59 |
| kcen | input-chancalan | 16.4 ± 0.6 | 15.4 | 19.4 | 15.39 ± 2.60 |
| kcen | input-kcen | 16.4 ± 0.5 | 15.2 | 19.1 | 15.40 ± 2.58 |
| kcen | input-aspidites | 16.4 ± 0.7 | 15.1 | 19.1 | 15.41 ± 2.62 |
| kcen | input-lanjian | 16.4 ± 0.6 | 15.5 | 19.3 | 15.44 ± 2.61 |


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