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
| mattcl | input-mattcl | 0.5 ± 0.3 | 0.0 | 0.9 | 1.00 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.0 | 1.29 ± 0.70 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 1.1 | 1.31 ± 0.71 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.1 | 0.9 | 1.32 ± 0.70 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.0 | 1.1 | 1.33 ± 0.70 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.4 | 1.35 ± 0.73 |
| mattcl | input-kcen | 0.7 ± 0.1 | 0.1 | 0.9 | 1.38 ± 0.72 |
| mattcl | input-pting | 0.7 ± 0.1 | 0.3 | 0.9 | 1.41 ± 0.72 |
| mattcl-ts | input-lanjian | 9.4 ± 0.4 | 8.4 | 10.4 | 17.76 ± 8.58 |
| mattcl-ts | input-mattcl | 9.4 ± 0.4 | 8.5 | 10.2 | 17.81 ± 8.60 |
| mattcl-ts | input-kcen | 9.5 ± 0.4 | 8.6 | 10.7 | 17.90 ± 8.65 |
| mattcl-ts | input-pting | 9.9 ± 4.7 | 8.5 | 66.3 | 18.73 ± 12.64 |
| kcen | input-lanjian | 13.8 ± 0.5 | 12.9 | 16.7 | 26.21 ± 12.65 |
| pting | input-mattcl | 13.9 ± 0.4 | 13.0 | 16.4 | 26.24 ± 12.65 |
| mattcl-py | input-lanjian | 13.9 ± 0.5 | 12.8 | 16.9 | 26.29 ± 12.69 |
| kcen | input-kcen | 13.9 ± 0.6 | 13.0 | 16.6 | 26.30 ± 12.71 |
| pting | input-kcen | 13.9 ± 0.4 | 12.9 | 16.4 | 26.32 ± 12.70 |
| pting | input-lanjian | 13.9 ± 0.6 | 13.0 | 17.1 | 26.33 ± 12.72 |
| mattcl-py | input-pting | 13.9 ± 0.5 | 13.3 | 17.1 | 26.38 ± 12.74 |
| mattcl-py | input-kcen | 13.9 ± 0.6 | 12.8 | 17.0 | 26.39 ± 12.76 |
| pting | input-pting | 13.9 ± 0.6 | 13.0 | 16.9 | 26.40 ± 12.76 |
| kcen | input-mattcl | 13.9 ± 0.7 | 12.9 | 17.8 | 26.41 ± 12.77 |
| kcen | input-pting | 14.0 ± 0.6 | 13.0 | 17.7 | 26.46 ± 12.80 |
| mattcl-py | input-mattcl | 14.4 ± 4.2 | 12.9 | 60.6 | 27.27 ± 15.37 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|