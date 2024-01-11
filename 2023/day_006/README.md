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
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.4 | 1.5 | 1.05 ± 0.31 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.3 | 1.2 | 1.05 ± 0.32 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.3 | 1.6 | 1.06 ± 0.32 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.7 | 1.06 ± 0.35 |
| lanjian | input-mikofo | 1.0 ± 0.1 | 0.5 | 1.4 | 1.07 ± 0.31 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.2 | 1.07 ± 0.32 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.4 | 1.7 | 1.07 ± 0.32 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.2 | 1.08 ± 0.32 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.3 | 1.1 | 1.11 ± 0.31 |
| mattcl-ts | input-mattcl | 10.1 ± 0.4 | 9.0 | 11.6 | 11.28 ± 2.81 |
| mattcl-ts | input-chancalan | 10.1 ± 0.3 | 9.0 | 11.0 | 11.32 ± 2.80 |
| mattcl-ts | input-kcen | 10.1 ± 0.3 | 9.0 | 11.1 | 11.34 ± 2.81 |
| mattcl-ts | input-mikofo | 10.1 ± 0.3 | 9.3 | 11.3 | 11.34 ± 2.81 |
| mattcl-ts | input-lanjian | 10.3 ± 2.7 | 9.3 | 47.9 | 11.55 ± 4.14 |
| pting | input-lanjian | 14.1 ± 0.6 | 13.0 | 17.0 | 15.79 ± 3.94 |
| pting | input-mikofo | 14.1 ± 0.5 | 13.0 | 17.3 | 15.79 ± 3.92 |
| chancalan | input-chancalan | 14.1 ± 0.6 | 13.4 | 17.5 | 15.82 ± 3.95 |
| kcen | input-lanjian | 14.1 ± 0.6 | 13.4 | 17.2 | 15.84 ± 3.94 |
| pting | input-kcen | 14.1 ± 0.6 | 13.2 | 17.3 | 15.84 ± 3.94 |
| kcen | input-chancalan | 14.2 ± 0.6 | 13.2 | 17.5 | 15.85 ± 3.95 |
| pting | input-chancalan | 14.2 ± 0.6 | 13.5 | 17.4 | 15.86 ± 3.95 |
| chancalan | input-mattcl | 14.2 ± 0.6 | 13.3 | 17.2 | 15.86 ± 3.96 |
| mattcl-py | input-mattcl | 14.2 ± 0.5 | 13.2 | 16.5 | 15.88 ± 3.95 |
| chancalan | input-kcen | 14.2 ± 0.6 | 13.2 | 17.6 | 15.88 ± 3.97 |
| mattcl-py | input-lanjian | 14.2 ± 0.6 | 13.1 | 17.6 | 15.90 ± 3.97 |
| chancalan | input-mikofo | 14.2 ± 0.7 | 13.3 | 17.5 | 15.90 ± 3.98 |
| chancalan | input-lanjian | 14.2 ± 0.8 | 13.1 | 17.7 | 15.90 ± 4.00 |
| kcen | input-kcen | 14.2 ± 0.6 | 13.5 | 17.4 | 15.90 ± 3.97 |
| kcen | input-mattcl | 14.2 ± 0.6 | 13.5 | 17.2 | 15.92 ± 3.98 |
| kcen | input-mikofo | 14.2 ± 0.6 | 13.5 | 17.5 | 15.94 ± 3.98 |
| mattcl-py | input-kcen | 14.2 ± 0.6 | 13.0 | 17.2 | 15.94 ± 3.98 |
| mattcl-py | input-mikofo | 14.2 ± 0.6 | 13.5 | 17.2 | 15.95 ± 3.99 |
| pting | input-mattcl | 14.3 ± 0.7 | 13.4 | 17.9 | 15.97 ± 4.01 |
| mattcl-py | input-chancalan | 14.3 ± 0.7 | 13.2 | 18.2 | 16.00 ± 4.02 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|