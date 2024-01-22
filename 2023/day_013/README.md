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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.5 | 1.5 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.33 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.4 | 1.06 ± 0.36 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.5 | 1.07 ± 0.36 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.7 | 1.16 ± 0.39 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.7 | 1.17 ± 0.39 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.17 ± 0.39 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.17 ± 0.39 |
| mattcl-py | input-kcen | 15.7 ± 0.6 | 14.5 | 18.4 | 17.90 ± 4.26 |
| mattcl-py | input-pting | 15.8 ± 0.6 | 14.5 | 18.8 | 17.98 ± 4.29 |
| mattcl-py | input-lanjian | 15.8 ± 0.8 | 14.5 | 18.9 | 18.04 ± 4.33 |
| mattcl-py | input-mattcl | 15.9 ± 0.7 | 14.8 | 18.7 | 18.09 ± 4.33 |
| pting | input-lanjian | 16.8 ± 0.6 | 15.5 | 20.5 | 19.12 ± 4.55 |
| pting | input-kcen | 16.9 ± 0.7 | 15.7 | 20.7 | 19.23 ± 4.59 |
| pting | input-pting | 17.0 ± 0.7 | 15.6 | 20.3 | 19.35 ± 4.62 |
| pting | input-mattcl | 17.0 ± 0.6 | 16.1 | 20.6 | 19.36 ± 4.60 |
| kcen | input-lanjian | 20.2 ± 0.8 | 19.0 | 23.1 | 22.98 ± 5.48 |
| kcen | input-kcen | 20.2 ± 0.7 | 19.1 | 22.7 | 22.98 ± 5.46 |
| kcen | input-mattcl | 20.4 ± 0.8 | 19.0 | 24.1 | 23.23 ± 5.54 |
| kcen | input-pting | 20.5 ± 0.8 | 19.2 | 24.1 | 23.28 ± 5.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|