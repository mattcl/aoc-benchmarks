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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.5 | 1.5 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.5 | 1.4 | 1.00 ± 0.32 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.4 | 1.04 ± 0.33 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.5 | 1.16 ± 0.36 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.6 | 1.6 | 1.18 ± 0.37 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.7 | 1.19 ± 0.38 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.7 | 1.20 ± 0.37 |
| mattcl | input-mattcl | 1.1 ± 4.7 | 0.5 | 66.5 | 1.34 ± 5.47 |
| mattcl-py | input-kcen | 15.5 ± 0.6 | 14.7 | 18.7 | 18.16 ± 4.07 |
| mattcl-py | input-lanjian | 15.5 ± 0.6 | 14.5 | 18.3 | 18.18 ± 4.08 |
| mattcl-py | input-pting | 15.5 ± 0.6 | 14.9 | 18.8 | 18.24 ± 4.09 |
| mattcl-py | input-mattcl | 15.6 ± 0.6 | 14.6 | 18.3 | 18.27 ± 4.10 |
| pting | input-lanjian | 16.7 ± 0.7 | 15.6 | 19.6 | 19.55 ± 4.40 |
| pting | input-pting | 16.8 ± 0.6 | 15.6 | 19.5 | 19.73 ± 4.41 |
| pting | input-mattcl | 16.9 ± 0.6 | 16.1 | 20.4 | 19.81 ± 4.44 |
| pting | input-kcen | 17.5 ± 5.5 | 15.6 | 66.6 | 20.56 ± 7.89 |
| kcen | input-kcen | 19.9 ± 0.5 | 18.7 | 22.5 | 23.33 ± 5.19 |
| kcen | input-pting | 20.1 ± 0.6 | 19.2 | 23.1 | 23.60 ± 5.26 |
| kcen | input-mattcl | 20.3 ± 0.8 | 19.0 | 23.2 | 23.84 ± 5.34 |
| kcen | input-lanjian | 20.3 ± 3.5 | 19.0 | 62.1 | 23.84 ± 6.71 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|