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

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.0 | 1.00 |
| lanjian | input-mikofo | 0.7 ± 0.2 | 0.1 | 1.0 | 1.02 ± 0.39 |
| lanjian | input-chancalan | 0.7 ± 0.2 | 0.1 | 1.2 | 1.04 ± 0.38 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.05 ± 0.39 |
| mattcl | input-mikofo | 0.8 ± 0.2 | 0.1 | 1.3 | 1.05 ± 0.42 |
| lanjian | input-kcen | 0.8 ± 0.1 | 0.3 | 0.9 | 1.09 ± 0.37 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.3 | 1.09 ± 0.41 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.2 | 1.10 ± 0.41 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.1 | 1.11 ± 0.40 |
| mattcl | input-kcen | 0.8 ± 0.1 | 0.1 | 1.0 | 1.18 ± 0.39 |
| mattcl-ts | input-mikofo | 9.6 ± 0.4 | 8.6 | 10.8 | 13.44 ± 3.92 |
| mattcl-ts | input-mattcl | 9.6 ± 0.4 | 8.7 | 10.8 | 13.45 ± 3.92 |
| mattcl-ts | input-kcen | 9.7 ± 0.4 | 8.5 | 10.8 | 13.50 ± 3.94 |
| mattcl-ts | input-lanjian | 9.7 ± 0.4 | 8.7 | 13.5 | 13.55 ± 3.97 |
| mattcl-ts | input-chancalan | 9.9 ± 3.3 | 8.6 | 56.1 | 13.86 ± 6.11 |
| pting | input-mikofo | 13.9 ± 0.4 | 13.0 | 17.1 | 19.35 ± 5.63 |
| chancalan | input-chancalan | 13.9 ± 0.6 | 12.9 | 17.5 | 19.39 ± 5.68 |
| mattcl-py | input-mikofo | 13.9 ± 0.6 | 13.0 | 17.8 | 19.39 ± 5.67 |
| kcen | input-chancalan | 13.9 ± 0.4 | 13.0 | 16.3 | 19.39 ± 5.64 |
| mattcl-py | input-kcen | 13.9 ± 0.5 | 12.8 | 17.7 | 19.39 ± 5.65 |
| pting | input-mattcl | 13.9 ± 0.5 | 12.9 | 17.0 | 19.40 ± 5.66 |
| pting | input-kcen | 13.9 ± 0.5 | 13.0 | 16.8 | 19.41 ± 5.66 |
| mattcl-py | input-chancalan | 13.9 ± 0.5 | 13.0 | 17.0 | 19.42 ± 5.66 |
| kcen | input-lanjian | 13.9 ± 0.6 | 13.0 | 16.8 | 19.42 ± 5.67 |
| chancalan | input-kcen | 13.9 ± 0.6 | 13.0 | 16.7 | 19.44 ± 5.68 |
| mattcl-py | input-mattcl | 13.9 ± 0.6 | 12.9 | 17.5 | 19.46 ± 5.68 |
| mattcl-py | input-lanjian | 13.9 ± 0.6 | 12.9 | 17.3 | 19.46 ± 5.69 |
| chancalan | input-mattcl | 14.0 ± 0.7 | 12.8 | 17.1 | 19.48 ± 5.72 |
| kcen | input-mikofo | 14.0 ± 0.6 | 13.1 | 17.6 | 19.49 ± 5.71 |
| kcen | input-kcen | 14.0 ± 0.6 | 13.0 | 17.2 | 19.49 ± 5.70 |
| chancalan | input-mikofo | 14.0 ± 0.6 | 12.9 | 16.9 | 19.50 ± 5.71 |
| chancalan | input-lanjian | 14.0 ± 0.7 | 12.9 | 17.2 | 19.52 ± 5.74 |
| pting | input-lanjian | 14.1 ± 1.7 | 12.9 | 36.7 | 19.65 ± 6.16 |
| kcen | input-mattcl | 14.1 ± 2.1 | 12.9 | 42.7 | 19.65 ± 6.40 |
| pting | input-chancalan | 14.1 ± 3.2 | 12.8 | 58.7 | 19.73 ± 7.26 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|