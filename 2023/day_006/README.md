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
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.1 | 1.01 ± 0.35 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.2 | 1.01 ± 0.34 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.02 ± 0.32 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.5 | 1.04 ± 0.34 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.0 | 1.05 ± 0.32 |
| lanjian | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.2 | 1.06 ± 0.30 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.2 | 1.06 ± 0.32 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.2 | 1.2 | 1.07 ± 0.30 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.4 | 1.07 ± 0.31 |
| mattcl-ts | input-chancalan | 9.9 ± 0.4 | 8.9 | 10.6 | 12.33 ± 2.84 |
| mattcl-ts | input-lanjian | 9.9 ± 0.4 | 8.8 | 10.7 | 12.35 ± 2.85 |
| mattcl-ts | input-pting | 9.9 ± 0.4 | 8.6 | 11.0 | 12.37 ± 2.86 |
| mattcl-ts | input-kcen | 9.9 ± 0.4 | 8.8 | 10.7 | 12.38 ± 2.85 |
| mattcl-ts | input-mattcl | 9.9 ± 0.4 | 8.8 | 10.8 | 12.39 ± 2.86 |
| chancalan | input-chancalan | 14.0 ± 0.5 | 13.0 | 17.2 | 17.45 ± 4.02 |
| chancalan | input-mattcl | 14.0 ± 0.5 | 13.5 | 17.1 | 17.48 ± 4.03 |
| pting | input-chancalan | 14.0 ± 0.5 | 13.2 | 17.6 | 17.50 ± 4.03 |
| mattcl-py | input-kcen | 14.0 ± 0.5 | 13.1 | 16.6 | 17.51 ± 4.03 |
| kcen | input-mattcl | 14.0 ± 0.5 | 12.9 | 16.9 | 17.51 ± 4.04 |
| mattcl-py | input-mattcl | 14.0 ± 0.6 | 13.3 | 17.3 | 17.53 ± 4.05 |
| pting | input-mattcl | 14.0 ± 0.5 | 13.4 | 17.3 | 17.53 ± 4.04 |
| mattcl-py | input-lanjian | 14.0 ± 0.6 | 13.0 | 17.5 | 17.53 ± 4.06 |
| kcen | input-lanjian | 14.0 ± 0.5 | 13.1 | 16.8 | 17.54 ± 4.05 |
| chancalan | input-kcen | 14.1 ± 0.6 | 12.8 | 17.1 | 17.56 ± 4.08 |
| chancalan | input-lanjian | 14.1 ± 0.6 | 12.9 | 17.4 | 17.58 ± 4.08 |
| kcen | input-chancalan | 14.1 ± 0.7 | 13.1 | 17.6 | 17.59 ± 4.09 |
| chancalan | input-pting | 14.1 ± 0.6 | 13.0 | 16.8 | 17.59 ± 4.08 |
| pting | input-lanjian | 14.1 ± 0.6 | 13.1 | 17.0 | 17.59 ± 4.07 |
| pting | input-pting | 14.1 ± 0.6 | 13.0 | 17.3 | 17.59 ± 4.07 |
| mattcl-py | input-pting | 14.1 ± 0.7 | 13.1 | 17.4 | 17.62 ± 4.10 |
| kcen | input-pting | 14.1 ± 0.7 | 13.0 | 17.7 | 17.64 ± 4.12 |
| kcen | input-kcen | 14.2 ± 0.8 | 13.3 | 17.7 | 17.72 ± 4.15 |
| mattcl-py | input-chancalan | 14.2 ± 2.7 | 13.0 | 51.3 | 17.78 ± 5.23 |
| pting | input-kcen | 14.3 ± 2.6 | 13.2 | 50.2 | 17.82 ± 5.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|