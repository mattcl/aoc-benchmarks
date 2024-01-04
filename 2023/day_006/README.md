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
| lanjian | input-mikofo | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.2 | 1.01 ± 0.33 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.03 ± 0.32 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.04 ± 0.30 |
| lanjian | input-mattcl | 0.8 ± 0.1 | 0.2 | 1.0 | 1.06 ± 0.30 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.2 | 1.08 ± 0.32 |
| mattcl | input-mikofo | 0.8 ± 0.2 | 0.1 | 1.5 | 1.08 ± 0.34 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.4 | 1.1 | 1.11 ± 0.30 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.11 ± 0.32 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.1 | 1.3 | 1.15 ± 0.30 |
| mattcl-ts | input-mattcl | 9.7 ± 0.4 | 8.7 | 10.6 | 12.41 ± 2.85 |
| mattcl-ts | input-kcen | 9.7 ± 0.3 | 8.7 | 10.5 | 12.46 ± 2.85 |
| mattcl-ts | input-lanjian | 9.7 ± 0.4 | 8.8 | 10.9 | 12.48 ± 2.86 |
| mattcl-ts | input-mikofo | 9.7 ± 0.4 | 8.7 | 10.5 | 12.49 ± 2.86 |
| mattcl-ts | input-chancalan | 9.8 ± 0.4 | 8.6 | 10.7 | 12.53 ± 2.87 |
| kcen | input-chancalan | 13.9 ± 0.4 | 13.1 | 17.0 | 17.82 ± 4.05 |
| chancalan | input-mattcl | 13.9 ± 0.5 | 12.9 | 16.9 | 17.83 ± 4.07 |
| chancalan | input-mikofo | 13.9 ± 0.4 | 12.9 | 16.4 | 17.84 ± 4.07 |
| mattcl-py | input-chancalan | 13.9 ± 0.5 | 13.0 | 17.1 | 17.85 ± 4.08 |
| pting | input-mattcl | 13.9 ± 0.5 | 13.0 | 16.8 | 17.85 ± 4.08 |
| kcen | input-kcen | 13.9 ± 0.6 | 12.9 | 17.2 | 17.86 ± 4.10 |
| chancalan | input-kcen | 13.9 ± 0.5 | 13.4 | 17.2 | 17.87 ± 4.08 |
| pting | input-mikofo | 13.9 ± 0.5 | 13.1 | 16.6 | 17.87 ± 4.08 |
| chancalan | input-chancalan | 13.9 ± 0.5 | 12.9 | 16.6 | 17.87 ± 4.09 |
| mattcl-py | input-mattcl | 13.9 ± 0.6 | 13.0 | 17.7 | 17.88 ± 4.10 |
| mattcl-py | input-lanjian | 13.9 ± 0.5 | 13.0 | 17.3 | 17.89 ± 4.10 |
| pting | input-lanjian | 14.0 ± 0.6 | 12.9 | 17.3 | 17.90 ± 4.11 |
| chancalan | input-lanjian | 14.0 ± 0.5 | 13.3 | 17.5 | 17.92 ± 4.11 |
| kcen | input-mikofo | 14.0 ± 0.6 | 13.3 | 17.1 | 17.93 ± 4.13 |
| kcen | input-mattcl | 14.0 ± 0.6 | 13.0 | 16.5 | 17.93 ± 4.11 |
| pting | input-kcen | 14.0 ± 0.6 | 13.0 | 17.1 | 17.94 ± 4.14 |
| mattcl-py | input-mikofo | 14.0 ± 0.7 | 12.9 | 17.7 | 17.98 ± 4.15 |
| pting | input-chancalan | 14.0 ± 0.7 | 13.4 | 16.9 | 18.00 ± 4.15 |
| mattcl-py | input-kcen | 14.1 ± 0.8 | 13.0 | 17.6 | 18.04 ± 4.20 |
| kcen | input-lanjian | 14.3 ± 3.2 | 12.8 | 47.7 | 18.29 ± 5.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|