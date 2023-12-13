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
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.0 | 1.01 ± 0.34 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.02 ± 0.34 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.5 | 1.02 ± 0.34 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.2 | 1.04 ± 0.35 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.2 | 1.5 | 1.04 ± 0.36 |
| lanjian | input-pting | 0.8 ± 0.1 | 0.3 | 1.2 | 1.05 ± 0.31 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.05 ± 0.34 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.2 | 1.0 | 1.10 ± 0.32 |
| lanjian | input-chancalan | 0.9 ± 3.2 | 0.1 | 46.3 | 1.10 ± 4.15 |
| mattcl-ts | input-lanjian | 9.9 ± 0.3 | 8.9 | 10.7 | 12.68 ± 3.22 |
| mattcl-ts | input-pting | 9.9 ± 0.3 | 8.9 | 10.8 | 12.68 ± 3.22 |
| mattcl-ts | input-kcen | 9.9 ± 0.4 | 9.1 | 11.0 | 12.70 ± 3.23 |
| mattcl-ts | input-mattcl | 10.0 ± 0.4 | 8.9 | 11.3 | 12.71 ± 3.23 |
| mattcl-ts | input-chancalan | 10.0 ± 0.4 | 8.8 | 11.5 | 12.75 ± 3.25 |
| chancalan | input-lanjian | 14.0 ± 0.4 | 13.3 | 17.6 | 17.85 ± 4.52 |
| pting | input-pting | 14.0 ± 0.5 | 13.0 | 16.9 | 17.85 ± 4.53 |
| mattcl-py | input-pting | 14.0 ± 0.5 | 12.9 | 17.1 | 17.87 ± 4.55 |
| mattcl-py | input-kcen | 14.0 ± 0.6 | 13.1 | 17.4 | 17.88 ± 4.56 |
| pting | input-mattcl | 14.0 ± 0.5 | 13.2 | 16.8 | 17.88 ± 4.55 |
| chancalan | input-mattcl | 14.0 ± 0.6 | 13.0 | 17.3 | 17.89 ± 4.57 |
| pting | input-chancalan | 14.0 ± 0.5 | 13.1 | 17.0 | 17.90 ± 4.54 |
| mattcl-py | input-lanjian | 14.0 ± 0.7 | 13.0 | 17.1 | 17.91 ± 4.59 |
| kcen | input-mattcl | 14.0 ± 0.6 | 13.5 | 17.4 | 17.92 ± 4.58 |
| chancalan | input-chancalan | 14.0 ± 0.7 | 13.0 | 18.1 | 17.93 ± 4.60 |
| kcen | input-kcen | 14.0 ± 0.6 | 13.2 | 17.1 | 17.93 ± 4.57 |
| mattcl-py | input-mattcl | 14.1 ± 0.7 | 12.9 | 17.6 | 17.94 ± 4.60 |
| kcen | input-pting | 14.1 ± 0.6 | 13.2 | 17.7 | 17.98 ± 4.59 |
| chancalan | input-kcen | 14.1 ± 0.7 | 13.0 | 17.3 | 17.99 ± 4.61 |
| chancalan | input-pting | 14.1 ± 1.4 | 13.0 | 33.2 | 18.01 ± 4.88 |
| pting | input-kcen | 14.1 ± 0.8 | 12.9 | 17.4 | 18.01 ± 4.64 |
| kcen | input-lanjian | 14.1 ± 0.7 | 13.2 | 17.1 | 18.03 ± 4.62 |
| pting | input-lanjian | 14.1 ± 0.7 | 13.1 | 17.3 | 18.04 ± 4.64 |
| mattcl-py | input-chancalan | 14.2 ± 3.1 | 13.3 | 56.8 | 18.15 ± 6.01 |
| kcen | input-chancalan | 14.3 ± 4.0 | 13.0 | 69.8 | 18.29 ± 6.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|