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
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.01 ± 0.32 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.1 | 1.01 ± 0.33 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.1 | 1.01 ± 0.34 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.0 | 1.03 ± 0.32 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.3 | 1.04 ± 0.32 |
| mattcl | input-mattcl | 0.8 ± 0.1 | 0.2 | 1.2 | 1.07 ± 0.31 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.2 | 1.2 | 1.11 ± 0.30 |
| mattcl-ts | input-pting | 9.4 ± 0.3 | 8.6 | 10.2 | 12.35 ± 2.94 |
| mattcl-ts | input-kcen | 9.4 ± 0.4 | 8.2 | 10.4 | 12.36 ± 2.94 |
| mattcl-ts | input-lanjian | 9.4 ± 0.3 | 8.5 | 10.2 | 12.36 ± 2.94 |
| mattcl-ts | input-mattcl | 9.6 ± 0.4 | 8.6 | 12.8 | 12.60 ± 3.02 |
| pting | input-lanjian | 13.9 ± 0.5 | 13.0 | 17.4 | 18.35 ± 4.37 |
| kcen | input-pting | 14.0 ± 0.4 | 12.9 | 16.8 | 18.39 ± 4.35 |
| kcen | input-kcen | 14.0 ± 0.5 | 13.1 | 16.9 | 18.40 ± 4.37 |
| pting | input-mattcl | 14.0 ± 0.5 | 12.9 | 16.9 | 18.41 ± 4.38 |
| mattcl-py | input-kcen | 14.0 ± 0.6 | 13.0 | 17.3 | 18.41 ± 4.40 |
| mattcl-py | input-mattcl | 14.0 ± 0.6 | 12.9 | 17.5 | 18.43 ± 4.40 |
| mattcl-py | input-lanjian | 14.0 ± 0.6 | 13.2 | 17.4 | 18.45 ± 4.40 |
| kcen | input-mattcl | 14.0 ± 0.5 | 12.9 | 17.4 | 18.46 ± 4.39 |
| pting | input-kcen | 14.0 ± 0.6 | 13.3 | 17.2 | 18.48 ± 4.41 |
| mattcl-py | input-pting | 14.0 ± 0.6 | 13.0 | 17.6 | 18.48 ± 4.42 |
| kcen | input-lanjian | 14.1 ± 0.6 | 13.3 | 17.2 | 18.51 ± 4.43 |
| pting | input-pting | 14.1 ± 0.6 | 13.1 | 17.1 | 18.52 ± 4.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|