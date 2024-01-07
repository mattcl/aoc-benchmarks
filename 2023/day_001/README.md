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
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.6 | 1.00 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.6 | 1.00 ± 0.26 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.26 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.4 | 1.02 ± 0.27 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.25 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.5 | 1.3 | 1.03 ± 0.25 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.5 | 1.2 | 1.03 ± 0.25 |
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.3 | 1.6 | 1.04 ± 0.26 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.3 | 1.2 | 1.04 ± 0.25 |
| mattcl | input-kcen | 1.1 ± 3.0 | 0.2 | 42.9 | 1.08 ± 3.02 |
| mattcl-ts | input-aspidites | 12.3 ± 0.4 | 11.1 | 13.4 | 12.43 ± 2.40 |
| mattcl-ts | input-mattcl | 12.4 ± 0.3 | 11.2 | 13.2 | 12.46 ± 2.40 |
| mikofo | input-mattcl | 12.4 ± 0.4 | 11.4 | 13.2 | 12.48 ± 2.41 |
| mikofo | input-kcen | 12.4 ± 0.4 | 11.4 | 13.8 | 12.49 ± 2.41 |
| mikofo | input-lanjian | 12.4 ± 0.3 | 11.2 | 13.6 | 12.49 ± 2.41 |
| mattcl-ts | input-kcen | 12.4 ± 0.3 | 11.4 | 13.1 | 12.49 ± 2.41 |
| mattcl-ts | input-chancalan | 12.4 ± 0.4 | 11.4 | 13.5 | 12.50 ± 2.41 |
| mikofo | input-aspidites | 12.4 ± 0.4 | 11.4 | 13.6 | 12.50 ± 2.41 |
| mattcl-ts | input-lanjian | 12.4 ± 0.3 | 11.6 | 13.2 | 12.52 ± 2.41 |
| mikofo | input-chancalan | 12.5 ± 0.4 | 11.4 | 13.4 | 12.54 ± 2.42 |
| aspidites | input-chancalan | 12.6 ± 0.5 | 11.7 | 14.3 | 12.67 ± 2.46 |
| aspidites | input-lanjian | 12.7 ± 0.4 | 11.7 | 14.0 | 12.76 ± 2.48 |
| aspidites | input-kcen | 12.7 ± 0.4 | 11.8 | 14.2 | 12.77 ± 2.48 |
| aspidites | input-aspidites | 12.7 ± 0.4 | 11.7 | 14.1 | 12.80 ± 2.48 |
| aspidites | input-mattcl | 12.7 ± 0.4 | 11.8 | 14.3 | 12.83 ± 2.48 |
| pting | input-lanjian | 15.4 ± 0.6 | 14.7 | 18.3 | 15.51 ± 3.01 |
| pting | input-aspidites | 15.4 ± 0.6 | 14.4 | 18.5 | 15.53 ± 3.03 |
| pting | input-mattcl | 15.5 ± 0.6 | 14.8 | 18.4 | 15.56 ± 3.03 |
| pting | input-chancalan | 15.5 ± 0.7 | 14.4 | 18.8 | 15.60 ± 3.06 |
| pting | input-kcen | 15.6 ± 0.7 | 14.7 | 18.4 | 15.67 ± 3.07 |
| chancalan | input-aspidites | 15.7 ± 0.6 | 14.6 | 18.6 | 15.84 ± 3.08 |
| chancalan | input-chancalan | 15.7 ± 0.7 | 14.6 | 18.8 | 15.84 ± 3.09 |
| chancalan | input-lanjian | 15.7 ± 0.7 | 14.7 | 18.7 | 15.86 ± 3.10 |
| mattcl-py | input-chancalan | 15.8 ± 0.6 | 14.8 | 18.5 | 15.88 ± 3.10 |
| chancalan | input-mattcl | 15.8 ± 0.7 | 14.8 | 19.0 | 15.89 ± 3.11 |
| mattcl-py | input-lanjian | 15.8 ± 0.8 | 14.7 | 18.9 | 15.90 ± 3.13 |
| mattcl-py | input-mattcl | 15.9 ± 0.7 | 14.6 | 18.5 | 15.96 ± 3.13 |
| mattcl-py | input-aspidites | 15.9 ± 0.8 | 14.9 | 19.5 | 15.99 ± 3.15 |
| mattcl-py | input-kcen | 16.0 ± 2.2 | 14.6 | 40.3 | 16.08 ± 3.76 |
| chancalan | input-kcen | 16.1 ± 3.0 | 14.5 | 55.6 | 16.25 ± 4.35 |
| kcen | input-chancalan | 16.3 ± 0.6 | 15.2 | 19.5 | 16.40 ± 3.18 |
| kcen | input-kcen | 16.3 ± 0.5 | 15.1 | 18.8 | 16.41 ± 3.17 |
| kcen | input-mattcl | 16.3 ± 0.6 | 15.3 | 19.6 | 16.42 ± 3.19 |
| kcen | input-lanjian | 16.4 ± 0.7 | 15.2 | 19.0 | 16.47 ± 3.22 |
| kcen | input-aspidites | 16.4 ± 0.6 | 15.1 | 19.0 | 16.48 ± 3.20 |


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