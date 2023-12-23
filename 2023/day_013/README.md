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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 ± 0.31 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.6 | 2.1 | 1.03 ± 0.34 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.6 | 1.04 ± 0.34 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 2.0 | 1.13 ± 0.36 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.14 ± 0.36 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.15 ± 0.37 |
| lanjian | input-mattcl | 1.1 ± 0.3 | 0.7 | 1.7 | 1.17 ± 0.38 |
| mattcl-py | input-kcen | 15.8 ± 0.8 | 14.7 | 19.2 | 16.70 ± 3.98 |
| mattcl-py | input-lanjian | 15.9 ± 0.8 | 14.7 | 18.9 | 16.79 ± 4.00 |
| mattcl-py | input-pting | 15.9 ± 0.7 | 14.8 | 18.9 | 16.82 ± 4.00 |
| mattcl-py | input-mattcl | 16.1 ± 0.8 | 14.9 | 19.4 | 17.04 ± 4.07 |
| pting | input-lanjian | 17.0 ± 0.6 | 16.2 | 19.4 | 17.97 ± 4.24 |
| pting | input-kcen | 17.0 ± 0.7 | 16.0 | 20.8 | 18.03 ± 4.27 |
| pting | input-pting | 17.2 ± 0.8 | 16.1 | 20.7 | 18.20 ± 4.33 |
| pting | input-mattcl | 17.3 ± 0.8 | 16.3 | 20.6 | 18.32 ± 4.36 |
| kcen | input-lanjian | 20.2 ± 0.7 | 19.0 | 22.9 | 21.37 ± 5.04 |
| kcen | input-kcen | 20.2 ± 0.7 | 19.2 | 23.6 | 21.41 ± 5.06 |
| kcen | input-mattcl | 20.3 ± 0.5 | 19.4 | 22.5 | 21.43 ± 5.04 |
| kcen | input-pting | 20.3 ± 0.7 | 19.4 | 23.3 | 21.46 ± 5.06 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|