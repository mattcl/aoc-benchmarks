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
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.2 | 1.00 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.30 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.0 | 1.02 ± 0.30 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.2 | 1.04 ± 0.31 |
| mattcl | input-kcen | 0.9 ± 3.2 | 0.1 | 46.1 | 1.07 ± 4.01 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.2 | 1.3 | 1.08 ± 0.29 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.2 | 1.3 | 1.08 ± 0.30 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.5 | 1.08 ± 0.32 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.6 | 1.09 ± 0.33 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.6 | 1.10 ± 0.31 |
| mattcl-ts | input-kcen | 9.7 ± 0.3 | 8.8 | 10.4 | 12.01 ± 2.73 |
| mattcl-ts | input-mattcl | 9.7 ± 0.4 | 8.7 | 10.6 | 12.04 ± 2.74 |
| mattcl-ts | input-pting | 9.7 ± 0.3 | 8.5 | 10.7 | 12.07 ± 2.74 |
| mattcl-ts | input-chancalan | 9.7 ± 0.4 | 8.8 | 10.8 | 12.08 ± 2.75 |
| mattcl-ts | input-lanjian | 9.7 ± 0.4 | 8.6 | 10.8 | 12.08 ± 2.75 |
| chancalan | input-chancalan | 14.0 ± 0.5 | 13.0 | 17.2 | 17.30 ± 3.93 |
| chancalan | input-pting | 14.0 ± 0.5 | 13.2 | 17.2 | 17.32 ± 3.94 |
| mattcl-py | input-chancalan | 14.0 ± 0.5 | 13.3 | 16.8 | 17.34 ± 3.93 |
| kcen | input-chancalan | 14.0 ± 0.4 | 12.9 | 16.4 | 17.35 ± 3.92 |
| chancalan | input-lanjian | 14.0 ± 0.5 | 12.9 | 16.7 | 17.35 ± 3.94 |
| chancalan | input-mattcl | 14.0 ± 0.5 | 13.1 | 16.8 | 17.35 ± 3.94 |
| mattcl-py | input-lanjian | 14.0 ± 0.5 | 13.2 | 16.5 | 17.35 ± 3.95 |
| pting | input-mattcl | 14.0 ± 0.5 | 13.0 | 16.8 | 17.36 ± 3.94 |
| mattcl-py | input-mattcl | 14.0 ± 0.6 | 13.1 | 17.6 | 17.37 ± 3.98 |
| pting | input-lanjian | 14.0 ± 0.6 | 13.0 | 17.3 | 17.39 ± 3.96 |
| pting | input-pting | 14.0 ± 0.7 | 12.9 | 17.5 | 17.39 ± 4.00 |
| chancalan | input-kcen | 14.0 ± 0.6 | 13.1 | 17.5 | 17.39 ± 3.97 |
| mattcl-py | input-pting | 14.0 ± 0.6 | 13.1 | 17.2 | 17.40 ± 3.97 |
| kcen | input-pting | 14.0 ± 0.6 | 13.0 | 17.2 | 17.40 ± 3.97 |
| pting | input-kcen | 14.1 ± 0.6 | 13.0 | 17.2 | 17.43 ± 3.99 |
| pting | input-chancalan | 14.1 ± 0.6 | 13.3 | 16.6 | 17.43 ± 3.98 |
| kcen | input-lanjian | 14.1 ± 0.6 | 13.4 | 17.4 | 17.44 ± 3.98 |
| kcen | input-mattcl | 14.1 ± 0.7 | 13.2 | 17.2 | 17.48 ± 4.00 |
| kcen | input-kcen | 14.2 ± 2.5 | 12.9 | 47.5 | 17.65 ± 5.02 |
| mattcl-py | input-kcen | 14.3 ± 2.4 | 13.0 | 43.1 | 17.75 ± 4.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|