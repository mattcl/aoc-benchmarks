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
| lanjian | input-pting | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 |
| lanjian | input-chancalan | 0.7 ± 0.2 | 0.1 | 1.4 | 1.09 ± 0.42 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.0 | 1.3 | 1.09 ± 0.42 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.3 | 1.10 ± 0.41 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.4 | 1.12 ± 0.43 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.4 | 1.12 ± 0.44 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.12 ± 0.41 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.3 | 1.13 ± 0.43 |
| lanjian | input-lanjian | 0.8 ± 0.1 | 0.2 | 1.0 | 1.15 ± 0.39 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.2 | 1.4 | 1.17 ± 0.41 |
| mattcl-ts | input-lanjian | 10.0 ± 0.3 | 9.1 | 11.5 | 14.44 ± 4.44 |
| mattcl-ts | input-chancalan | 10.0 ± 0.3 | 9.1 | 10.8 | 14.45 ± 4.44 |
| mattcl-ts | input-pting | 10.0 ± 0.4 | 8.8 | 11.1 | 14.46 ± 4.45 |
| mattcl-ts | input-kcen | 10.0 ± 0.3 | 9.1 | 10.8 | 14.48 ± 4.45 |
| mattcl-ts | input-mattcl | 10.0 ± 0.3 | 9.2 | 10.8 | 14.48 ± 4.45 |
| chancalan | input-lanjian | 14.0 ± 0.6 | 13.1 | 16.7 | 20.32 ± 6.26 |
| chancalan | input-chancalan | 14.1 ± 0.4 | 13.2 | 15.9 | 20.34 ± 6.25 |
| chancalan | input-pting | 14.1 ± 0.6 | 13.0 | 17.1 | 20.35 ± 6.27 |
| pting | input-chancalan | 14.1 ± 0.6 | 12.9 | 17.5 | 20.36 ± 6.28 |
| chancalan | input-kcen | 14.1 ± 0.5 | 12.9 | 16.9 | 20.41 ± 6.29 |
| mattcl-py | input-kcen | 14.1 ± 0.6 | 13.2 | 17.5 | 20.41 ± 6.29 |
| chancalan | input-mattcl | 14.1 ± 0.7 | 13.0 | 17.6 | 20.42 ± 6.32 |
| pting | input-mattcl | 14.1 ± 0.6 | 12.9 | 17.6 | 20.42 ± 6.30 |
| kcen | input-lanjian | 14.1 ± 0.5 | 13.1 | 17.5 | 20.43 ± 6.29 |
| mattcl-py | input-lanjian | 14.1 ± 0.7 | 12.9 | 17.6 | 20.46 ± 6.34 |
| kcen | input-chancalan | 14.2 ± 0.6 | 13.2 | 17.7 | 20.49 ± 6.33 |
| mattcl-py | input-pting | 14.2 ± 0.6 | 13.0 | 17.3 | 20.50 ± 6.32 |
| mattcl-py | input-chancalan | 14.2 ± 0.6 | 13.4 | 17.4 | 20.51 ± 6.33 |
| kcen | input-pting | 14.2 ± 0.7 | 13.1 | 18.5 | 20.51 ± 6.36 |
| pting | input-kcen | 14.2 ± 0.7 | 13.1 | 17.9 | 20.51 ± 6.35 |
| pting | input-lanjian | 14.2 ± 0.7 | 13.0 | 17.4 | 20.52 ± 6.36 |
| mattcl-py | input-mattcl | 14.2 ± 0.7 | 13.0 | 17.3 | 20.54 ± 6.36 |
| pting | input-pting | 14.2 ± 0.7 | 13.1 | 18.5 | 20.57 ± 6.36 |
| kcen | input-mattcl | 14.3 ± 0.7 | 12.9 | 17.4 | 20.63 ± 6.39 |
| kcen | input-kcen | 14.3 ± 1.6 | 12.9 | 35.3 | 20.73 ± 6.77 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|