# Day 6 benchmarks

[link to problem](https://adventofcode.com/2023/day/6)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 6)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-kcen | 0.6 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-pting | 0.6 ± 0.2 | 0.2 | 1.6 | 1.11 ± 0.58 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.2 | 1.1 | 1.13 ± 0.56 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.2 | 1.6 | 1.21 ± 0.61 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.2 | 1.3 | 1.28 ± 0.63 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.3 | 1.38 ± 0.63 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.3 | 1.0 | 1.45 ± 0.62 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.3 | 1.48 ± 0.63 |
| mattcl-ts | input-lanjian | 9.3 ± 0.4 | 8.3 | 10.4 | 16.05 ± 6.15 |
| mattcl-ts | input-kcen | 9.3 ± 0.4 | 8.0 | 10.6 | 16.10 ± 6.16 |
| mattcl-ts | input-mattcl | 9.4 ± 0.4 | 8.2 | 10.9 | 16.29 ± 6.24 |
| mattcl-ts | input-pting | 9.8 ± 2.9 | 8.5 | 50.4 | 16.97 ± 8.20 |
| kcen | input-lanjian | 14.1 ± 0.6 | 13.2 | 17.5 | 24.37 ± 9.34 |
| mattcl-py | input-mattcl | 14.1 ± 0.5 | 13.1 | 17.0 | 24.38 ± 9.33 |
| kcen | input-kcen | 14.1 ± 0.6 | 13.0 | 16.6 | 24.39 ± 9.34 |
| kcen | input-mattcl | 14.1 ± 0.4 | 13.1 | 16.4 | 24.50 ± 9.36 |
| pting | input-kcen | 14.2 ± 0.5 | 13.1 | 16.3 | 24.54 ± 9.39 |
| mattcl-py | input-kcen | 14.2 ± 0.5 | 13.3 | 17.2 | 24.64 ± 9.43 |
| pting | input-lanjian | 14.6 ± 0.6 | 13.3 | 17.1 | 25.33 ± 9.70 |
| pting | input-mattcl | 14.6 ± 2.9 | 13.2 | 53.8 | 25.34 ± 10.88 |
| mattcl-py | input-lanjian | 14.7 ± 2.5 | 13.3 | 48.6 | 25.39 ± 10.59 |
| kcen | input-pting | 14.8 ± 1.4 | 13.1 | 29.1 | 25.60 ± 10.06 |
| mattcl-py | input-pting | 14.9 ± 0.5 | 13.6 | 16.9 | 25.76 ± 9.85 |
| pting | input-pting | 15.1 ± 3.1 | 13.5 | 50.3 | 26.19 ± 11.36 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|