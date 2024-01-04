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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.00 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.02 ± 0.31 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.5 | 1.02 ± 0.30 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.03 ± 0.30 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.8 | 1.09 ± 0.33 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.8 | 1.8 | 1.09 ± 0.32 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.12 ± 0.33 |
| lanjian | input-pting | 1.2 ± 0.3 | 0.8 | 1.8 | 1.13 ± 0.34 |
| mattcl-py | input-lanjian | 15.8 ± 0.5 | 14.8 | 18.4 | 15.49 ± 3.21 |
| mattcl-py | input-kcen | 15.9 ± 0.7 | 14.7 | 18.3 | 15.63 ± 3.27 |
| mattcl-py | input-mattcl | 15.9 ± 0.6 | 14.6 | 18.2 | 15.65 ± 3.26 |
| mattcl-py | input-pting | 16.0 ± 0.8 | 14.8 | 19.7 | 15.73 ± 3.32 |
| pting | input-lanjian | 16.9 ± 0.6 | 16.1 | 20.0 | 16.65 ± 3.46 |
| pting | input-kcen | 17.1 ± 0.7 | 16.1 | 20.0 | 16.77 ± 3.50 |
| pting | input-mattcl | 17.3 ± 0.7 | 16.1 | 19.9 | 16.96 ± 3.54 |
| pting | input-pting | 17.4 ± 1.8 | 16.3 | 39.5 | 17.05 ± 3.93 |
| kcen | input-kcen | 20.3 ± 0.7 | 19.4 | 23.4 | 19.97 ± 4.16 |
| kcen | input-lanjian | 20.4 ± 0.8 | 19.3 | 23.4 | 20.03 ± 4.19 |
| kcen | input-pting | 20.5 ± 0.7 | 19.5 | 24.0 | 20.09 ± 4.18 |
| kcen | input-mattcl | 21.3 ± 3.4 | 19.0 | 54.9 | 20.93 ± 5.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|