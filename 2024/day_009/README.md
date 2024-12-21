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
| mattcl | input-kcen | 2.2 ± 0.3 | 1.3 | 3.8 | 1.00 |
| mattcl | input-lanjian | 2.2 ± 0.3 | 1.4 | 3.7 | 1.01 ± 0.22 |
| mattcl | input-mattcl | 2.3 ± 0.3 | 1.4 | 3.1 | 1.02 ± 0.22 |
| lanjian | input-kcen | 2.5 ± 0.3 | 1.6 | 4.0 | 1.13 ± 0.23 |
| lanjian | input-mattcl | 2.5 ± 0.3 | 1.6 | 4.1 | 1.15 ± 0.22 |
| lanjian | input-lanjian | 2.5 ± 0.2 | 1.7 | 3.1 | 1.15 ± 0.21 |
| kcen | input-mattcl | 3.9 ± 0.4 | 3.0 | 6.7 | 1.75 ± 0.33 |
| kcen | input-lanjian | 3.9 ± 0.4 | 3.0 | 7.1 | 1.76 ± 0.33 |
| kcen | input-kcen | 4.1 ± 0.4 | 3.2 | 6.7 | 1.84 ± 0.34 |
| mattcl-py | input-lanjian | 31.4 ± 1.0 | 29.9 | 34.5 | 14.21 ± 2.24 |
| mattcl-py | input-mattcl | 31.6 ± 1.0 | 30.1 | 34.5 | 14.34 ± 2.26 |
| mattcl-py | input-kcen | 31.6 ± 1.1 | 30.0 | 36.0 | 14.34 ± 2.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|