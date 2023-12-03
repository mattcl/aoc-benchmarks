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
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.3 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.4 | 1.04 ± 0.32 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.2 | 1.04 ± 0.31 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.4 | 1.05 ± 0.31 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.7 | 1.06 ± 0.32 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.3 | 2.0 | 1.08 ± 0.33 |
| lanjian | input-chancalan | 1.8 ± 0.1 | 1.3 | 2.5 | 1.94 ± 0.48 |
| lanjian | input-aspidites | 1.9 ± 0.2 | 1.1 | 2.7 | 2.03 ± 0.54 |
| lanjian | input-pting | 1.9 ± 0.2 | 1.4 | 2.8 | 2.04 ± 0.54 |
| lanjian | input-mattcl | 1.9 ± 0.2 | 1.3 | 3.0 | 2.06 ± 0.55 |
| lanjian | input-lanjian | 1.9 ± 0.3 | 1.2 | 2.8 | 2.07 ± 0.57 |
| lanjian | input-kcen | 1.9 ± 0.3 | 1.7 | 2.7 | 2.08 ± 0.57 |
| aspidites | input-chancalan | 13.0 ± 0.4 | 11.9 | 14.4 | 13.95 ± 3.35 |
| aspidites | input-pting | 13.0 ± 0.4 | 12.1 | 14.4 | 13.98 ± 3.36 |
| aspidites | input-kcen | 13.1 ± 0.5 | 11.5 | 14.1 | 14.01 ± 3.37 |
| aspidites | input-aspidites | 13.1 ± 0.5 | 12.0 | 14.6 | 14.02 ± 3.38 |
| aspidites | input-lanjian | 13.1 ± 0.4 | 12.1 | 14.9 | 14.06 ± 3.38 |
| aspidites | input-mattcl | 13.2 ± 1.6 | 12.0 | 35.4 | 14.11 ± 3.80 |
| pting | input-kcen | 17.8 ± 0.5 | 16.9 | 21.0 | 19.11 ± 4.59 |
| pting | input-pting | 17.9 ± 0.7 | 16.8 | 21.5 | 19.23 ± 4.64 |
| pting | input-aspidites | 18.0 ± 0.8 | 16.9 | 20.9 | 19.24 ± 4.67 |
| pting | input-mattcl | 18.0 ± 0.7 | 17.1 | 20.7 | 19.27 ± 4.65 |
| pting | input-chancalan | 18.0 ± 0.8 | 17.0 | 21.3 | 19.30 ± 4.68 |
| pting | input-lanjian | 18.1 ± 2.8 | 16.7 | 52.6 | 19.43 ± 5.53 |
| mattcl-py | input-kcen | 18.5 ± 0.6 | 17.6 | 22.0 | 19.79 ± 4.76 |
| chancalan | input-aspidites | 18.5 ± 0.6 | 17.5 | 21.1 | 19.81 ± 4.77 |
| mattcl-py | input-lanjian | 18.5 ± 0.6 | 17.7 | 21.6 | 19.81 ± 4.76 |
| chancalan | input-kcen | 18.5 ± 0.7 | 17.5 | 22.0 | 19.82 ± 4.77 |
| mattcl-py | input-aspidites | 18.5 ± 0.8 | 17.3 | 21.5 | 19.85 ± 4.80 |
| chancalan | input-pting | 18.5 ± 0.7 | 17.6 | 21.4 | 19.85 ± 4.78 |
| mattcl-py | input-pting | 18.6 ± 0.8 | 17.4 | 21.8 | 19.89 ± 4.81 |
| chancalan | input-lanjian | 18.6 ± 0.7 | 17.7 | 21.7 | 19.90 ± 4.80 |
| chancalan | input-chancalan | 18.6 ± 0.8 | 17.7 | 21.4 | 19.91 ± 4.81 |
| mattcl-py | input-chancalan | 18.6 ± 0.8 | 17.4 | 21.5 | 19.91 ± 4.81 |
| chancalan | input-mattcl | 18.6 ± 0.7 | 17.7 | 21.8 | 19.91 ± 4.81 |
| mattcl-py | input-mattcl | 18.6 ± 0.7 | 17.5 | 21.6 | 19.92 ± 4.81 |
| kcen | input-lanjian | 18.7 ± 0.6 | 17.7 | 21.9 | 20.08 ± 4.83 |
| kcen | input-mattcl | 18.8 ± 0.6 | 17.9 | 21.7 | 20.10 ± 4.83 |
| kcen | input-chancalan | 18.8 ± 0.7 | 17.7 | 21.8 | 20.12 ± 4.85 |
| kcen | input-aspidites | 18.8 ± 0.7 | 17.7 | 21.6 | 20.16 ± 4.87 |
| kcen | input-kcen | 18.8 ± 0.8 | 17.7 | 22.6 | 20.16 ± 4.87 |
| kcen | input-pting | 18.8 ± 0.7 | 17.8 | 22.1 | 20.20 ± 4.87 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|