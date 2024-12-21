# Day 9 benchmarks

[link to problem](https://adventofcode.com/2024/day/9)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 9)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-kcen | 2.1 ± 0.3 | 1.4 | 3.1 | 1.00 |
| mattcl | input-mattcl | 2.2 ± 0.3 | 1.2 | 2.8 | 1.02 ± 0.22 |
| mattcl | input-lanjian | 2.2 ± 0.3 | 1.4 | 3.1 | 1.02 ± 0.23 |
| lanjian | input-mattcl | 2.5 ± 0.3 | 1.6 | 4.2 | 1.17 ± 0.23 |
| lanjian | input-kcen | 2.5 ± 0.3 | 1.6 | 3.8 | 1.18 ± 0.22 |
| lanjian | input-lanjian | 2.5 ± 0.3 | 1.5 | 4.2 | 1.19 ± 0.24 |
| kcen | input-lanjian | 3.8 ± 0.5 | 2.9 | 7.2 | 1.80 ± 0.36 |
| kcen | input-kcen | 3.9 ± 0.3 | 3.2 | 5.5 | 1.81 ± 0.32 |
| kcen | input-mattcl | 3.9 ± 0.4 | 3.1 | 5.9 | 1.82 ± 0.34 |
| mattcl-py | input-mattcl | 31.3 ± 0.7 | 30.3 | 34.4 | 14.71 ± 2.31 |
| mattcl-py | input-lanjian | 31.4 ± 0.8 | 30.1 | 34.2 | 14.75 ± 2.33 |
| mattcl-py | input-kcen | 31.4 ± 0.8 | 30.4 | 35.2 | 14.76 ± 2.33 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|