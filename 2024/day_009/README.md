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
| mattcl | input-lanjian | 2.4 ± 0.4 | 1.6 | 4.3 | 1.00 |
| mattcl | input-mattcl | 2.4 ± 0.4 | 1.6 | 3.3 | 1.00 ± 0.21 |
| mattcl | input-kcen | 2.4 ± 0.3 | 1.6 | 3.1 | 1.01 ± 0.20 |
| lanjian | input-kcen | 2.8 ± 0.3 | 1.8 | 4.1 | 1.14 ± 0.20 |
| lanjian | input-lanjian | 2.8 ± 0.3 | 1.8 | 3.8 | 1.14 ± 0.20 |
| lanjian | input-mattcl | 2.8 ± 0.3 | 1.8 | 4.7 | 1.15 ± 0.21 |
| kcen | input-mattcl | 3.9 ± 0.5 | 2.9 | 6.8 | 1.60 ± 0.30 |
| kcen | input-kcen | 4.0 ± 0.5 | 3.1 | 6.9 | 1.66 ± 0.33 |
| kcen | input-lanjian | 4.0 ± 0.2 | 3.3 | 4.7 | 1.67 ± 0.26 |
| mattcl-py | input-mattcl | 31.6 ± 0.6 | 30.4 | 34.2 | 13.04 ± 1.93 |
| mattcl-py | input-lanjian | 31.7 ± 0.8 | 30.5 | 34.4 | 13.09 ± 1.94 |
| mattcl-py | input-kcen | 31.9 ± 0.9 | 30.6 | 34.5 | 13.17 ± 1.97 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|