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
| mattcl | input-mattcl | 2.3 ± 0.4 | 1.7 | 4.4 | 1.00 |
| mattcl | input-kcen | 2.3 ± 0.4 | 1.3 | 3.2 | 1.02 ± 0.23 |
| mattcl | input-lanjian | 2.3 ± 0.4 | 1.5 | 3.8 | 1.03 ± 0.23 |
| lanjian | input-kcen | 2.6 ± 0.3 | 1.6 | 5.0 | 1.15 ± 0.23 |
| lanjian | input-lanjian | 2.6 ± 0.2 | 1.7 | 3.2 | 1.16 ± 0.21 |
| lanjian | input-mattcl | 2.6 ± 0.3 | 1.7 | 4.6 | 1.16 ± 0.22 |
| kcen | input-lanjian | 3.9 ± 0.5 | 3.0 | 7.2 | 1.72 ± 0.35 |
| kcen | input-mattcl | 4.1 ± 0.4 | 3.2 | 5.5 | 1.79 ± 0.33 |
| kcen | input-kcen | 4.1 ± 0.4 | 3.2 | 6.7 | 1.80 ± 0.34 |
| mattcl-py | input-kcen | 31.6 ± 0.9 | 30.4 | 35.0 | 13.92 ± 2.25 |
| mattcl-py | input-lanjian | 31.7 ± 0.8 | 30.5 | 34.2 | 13.96 ± 2.25 |
| mattcl-py | input-mattcl | 31.9 ± 1.0 | 30.4 | 35.2 | 14.04 ± 2.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|