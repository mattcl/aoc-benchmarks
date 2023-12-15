# Day 13 benchmarks

[link to problem](https://adventofcode.com/2023/day/13)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 13)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 ± 0.30 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.32 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.6 | 1.5 | 1.04 ± 0.33 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.6 | 1.15 ± 0.34 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.16 ± 0.35 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.6 | 1.17 ± 0.36 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.17 ± 0.36 |
| mattcl-py | input-kcen | 15.6 ± 0.5 | 14.5 | 18.5 | 16.66 ± 3.68 |
| mattcl-py | input-lanjian | 15.7 ± 0.6 | 14.5 | 18.3 | 16.80 ± 3.73 |
| mattcl-py | input-mattcl | 15.8 ± 0.6 | 15.0 | 18.7 | 16.88 ± 3.75 |
| mattcl-py | input-pting | 15.8 ± 0.8 | 14.6 | 18.8 | 16.89 ± 3.78 |
| pting | input-kcen | 16.7 ± 0.5 | 16.0 | 19.7 | 17.87 ± 3.94 |
| pting | input-lanjian | 16.7 ± 0.6 | 15.7 | 19.7 | 17.89 ± 3.97 |
| pting | input-mattcl | 16.9 ± 0.5 | 16.1 | 19.0 | 18.06 ± 3.97 |
| pting | input-pting | 17.0 ± 0.8 | 15.9 | 20.5 | 18.18 ± 4.05 |
| kcen | input-lanjian | 20.0 ± 0.6 | 19.2 | 22.5 | 21.37 ± 4.72 |
| kcen | input-kcen | 20.1 ± 0.7 | 18.9 | 22.7 | 21.46 ± 4.75 |
| kcen | input-pting | 20.1 ± 0.5 | 19.2 | 22.6 | 21.50 ± 4.73 |
| kcen | input-mattcl | 20.2 ± 0.5 | 19.2 | 22.7 | 21.62 ± 4.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|