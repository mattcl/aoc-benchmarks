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
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.1 | 1.00 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.0 | 1.01 ± 0.33 |
| lanjian | input-mikofo | 0.8 ± 0.2 | 0.1 | 1.0 | 1.02 ± 0.31 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.2 | 1.02 ± 0.31 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.0 | 1.03 ± 0.30 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.4 | 1.05 ± 0.35 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.1 | 1.0 | 1.08 ± 0.33 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.5 | 1.09 ± 0.34 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.2 | 1.3 | 1.10 ± 0.31 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.2 | 1.1 | 1.14 ± 0.29 |
| mattcl-ts | input-kcen | 9.8 ± 0.4 | 9.0 | 11.4 | 12.48 ± 2.83 |
| mattcl-ts | input-lanjian | 9.9 ± 0.3 | 8.7 | 10.6 | 12.50 ± 2.82 |
| mattcl-ts | input-chancalan | 9.9 ± 0.4 | 8.9 | 11.2 | 12.54 ± 2.83 |
| mattcl-ts | input-mattcl | 9.9 ± 0.3 | 8.9 | 10.7 | 12.54 ± 2.83 |
| mattcl-ts | input-mikofo | 9.9 ± 0.3 | 8.9 | 11.2 | 12.60 ± 2.85 |
| kcen | input-chancalan | 13.9 ± 0.5 | 12.9 | 17.3 | 17.62 ± 3.98 |
| kcen | input-lanjian | 13.9 ± 0.5 | 13.0 | 17.2 | 17.64 ± 3.99 |
| chancalan | input-kcen | 13.9 ± 0.6 | 13.1 | 18.0 | 17.65 ± 4.00 |
| chancalan | input-mikofo | 13.9 ± 0.6 | 13.1 | 16.5 | 17.66 ± 4.00 |
| mattcl-py | input-lanjian | 13.9 ± 0.5 | 13.0 | 17.0 | 17.66 ± 3.99 |
| mattcl-py | input-mikofo | 13.9 ± 0.5 | 13.3 | 16.8 | 17.66 ± 3.99 |
| pting | input-mattcl | 13.9 ± 0.6 | 13.0 | 17.7 | 17.67 ± 4.02 |
| mattcl-py | input-kcen | 13.9 ± 0.5 | 13.2 | 16.8 | 17.67 ± 4.00 |
| pting | input-mikofo | 13.9 ± 0.6 | 12.9 | 17.8 | 17.67 ± 4.01 |
| kcen | input-mikofo | 13.9 ± 0.6 | 13.1 | 17.4 | 17.68 ± 4.01 |
| kcen | input-kcen | 14.0 ± 0.6 | 13.1 | 16.9 | 17.70 ± 4.02 |
| chancalan | input-chancalan | 14.0 ± 0.6 | 13.3 | 17.2 | 17.72 ± 4.04 |
| kcen | input-mattcl | 14.0 ± 0.6 | 12.9 | 16.9 | 17.72 ± 4.03 |
| pting | input-chancalan | 14.0 ± 0.6 | 12.8 | 16.8 | 17.73 ± 4.03 |
| pting | input-lanjian | 14.0 ± 0.6 | 13.0 | 17.3 | 17.74 ± 4.03 |
| pting | input-kcen | 14.0 ± 0.7 | 12.8 | 17.3 | 17.76 ± 4.06 |
| chancalan | input-lanjian | 14.0 ± 2.0 | 12.9 | 40.8 | 17.80 ± 4.70 |
| mattcl-py | input-chancalan | 14.0 ± 0.8 | 13.0 | 17.4 | 17.81 ± 4.09 |
| mattcl-py | input-mattcl | 14.2 ± 2.3 | 12.8 | 44.3 | 17.96 ± 4.94 |
| chancalan | input-mattcl | 14.3 ± 3.9 | 13.3 | 68.2 | 18.15 ± 6.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|