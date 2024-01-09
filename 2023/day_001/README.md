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
| lanjian | input-aspidites | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.4 | 1.6 | 1.01 ± 0.26 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.27 |
| mattcl | input-aspidites | 1.1 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.26 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.27 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.6 | 1.03 ± 0.26 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.26 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.7 | 1.04 ± 0.25 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.5 | 1.5 | 1.04 ± 0.25 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.6 | 1.7 | 1.06 ± 0.25 |
| mattcl-ts | input-lanjian | 12.7 ± 0.3 | 11.6 | 13.7 | 12.03 ± 2.37 |
| mattcl-ts | input-mattcl | 12.7 ± 0.3 | 12.0 | 13.5 | 12.05 ± 2.36 |
| mattcl-ts | input-kcen | 12.7 ± 0.3 | 12.1 | 13.8 | 12.06 ± 2.37 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 11.7 | 13.7 | 12.07 ± 2.37 |
| mattcl-ts | input-aspidites | 12.7 ± 0.3 | 12.0 | 13.7 | 12.09 ± 2.38 |
| aspidites | input-kcen | 12.7 ± 0.4 | 11.6 | 14.1 | 12.10 ± 2.40 |
| aspidites | input-mattcl | 12.8 ± 0.5 | 11.6 | 14.2 | 12.13 ± 2.41 |
| aspidites | input-chancalan | 12.8 ± 0.4 | 11.9 | 14.1 | 12.19 ± 2.41 |
| aspidites | input-aspidites | 12.9 ± 0.5 | 11.7 | 15.0 | 12.24 ± 2.43 |
| mikofo | input-lanjian | 12.9 ± 0.4 | 11.9 | 13.9 | 12.26 ± 2.42 |
| mikofo | input-kcen | 13.0 ± 0.4 | 12.0 | 14.4 | 12.30 ± 2.42 |
| mikofo | input-mattcl | 13.0 ± 0.4 | 11.9 | 13.9 | 12.35 ± 2.44 |
| aspidites | input-lanjian | 13.0 ± 2.8 | 11.2 | 42.3 | 12.36 ± 3.60 |
| mikofo | input-chancalan | 13.0 ± 0.3 | 12.2 | 13.9 | 12.36 ± 2.43 |
| mikofo | input-aspidites | 13.0 ± 0.3 | 12.2 | 13.8 | 12.38 ± 2.43 |
| pting | input-lanjian | 15.8 ± 0.6 | 14.9 | 18.7 | 14.99 ± 2.97 |
| pting | input-aspidites | 15.8 ± 0.6 | 14.7 | 19.0 | 15.00 ± 2.97 |
| pting | input-kcen | 15.8 ± 0.7 | 14.7 | 18.6 | 15.03 ± 3.00 |
| pting | input-mattcl | 15.9 ± 0.7 | 14.5 | 18.4 | 15.08 ± 3.01 |
| pting | input-chancalan | 15.9 ± 0.7 | 14.7 | 18.6 | 15.10 ± 3.01 |
| chancalan | input-mattcl | 16.1 ± 0.6 | 15.2 | 18.7 | 15.25 ± 3.02 |
| mattcl-py | input-chancalan | 16.1 ± 0.6 | 14.8 | 19.7 | 15.26 ± 3.04 |
| mattcl-py | input-aspidites | 16.1 ± 0.8 | 14.8 | 19.6 | 15.26 ± 3.08 |
| mattcl-py | input-lanjian | 16.1 ± 0.5 | 15.0 | 18.6 | 15.32 ± 3.03 |
| chancalan | input-aspidites | 16.1 ± 0.7 | 14.9 | 19.5 | 15.32 ± 3.07 |
| mattcl-py | input-kcen | 16.1 ± 0.7 | 15.0 | 19.9 | 15.34 ± 3.06 |
| chancalan | input-chancalan | 16.2 ± 0.6 | 15.0 | 19.4 | 15.38 ± 3.06 |
| mattcl-py | input-mattcl | 16.2 ± 0.7 | 15.1 | 18.8 | 15.38 ± 3.08 |
| chancalan | input-kcen | 16.3 ± 0.8 | 15.0 | 19.3 | 15.47 ± 3.11 |
| chancalan | input-lanjian | 16.4 ± 2.9 | 14.7 | 48.4 | 15.59 ± 4.08 |
| kcen | input-lanjian | 16.5 ± 0.6 | 15.5 | 19.7 | 15.71 ± 3.12 |
| kcen | input-mattcl | 16.6 ± 0.6 | 15.2 | 19.4 | 15.76 ± 3.13 |
| kcen | input-aspidites | 16.6 ± 0.6 | 15.3 | 19.7 | 15.77 ± 3.13 |
| kcen | input-chancalan | 16.7 ± 0.7 | 15.8 | 19.9 | 15.85 ± 3.17 |
| kcen | input-kcen | 16.7 ± 0.8 | 15.6 | 20.3 | 15.90 ± 3.18 |


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