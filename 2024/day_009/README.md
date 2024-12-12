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
| mattcl | input-kcen | 2.2 ± 0.3 | 1.4 | 2.9 | 1.00 |
| mattcl | input-lanjian | 2.2 ± 0.4 | 1.2 | 3.3 | 1.00 ± 0.23 |
| mattcl | input-mattcl | 2.2 ± 0.4 | 1.4 | 3.9 | 1.03 ± 0.24 |
| lanjian | input-mattcl | 2.5 ± 0.3 | 1.3 | 3.2 | 1.15 ± 0.22 |
| lanjian | input-lanjian | 2.5 ± 0.3 | 1.4 | 4.6 | 1.17 ± 0.24 |
| lanjian | input-kcen | 2.5 ± 0.3 | 1.7 | 4.4 | 1.18 ± 0.21 |
| kcen | input-lanjian | 4.5 ± 0.5 | 3.6 | 7.3 | 2.08 ± 0.39 |
| kcen | input-mattcl | 4.7 ± 0.5 | 3.9 | 7.6 | 2.19 ± 0.40 |
| kcen | input-kcen | 4.9 ± 0.5 | 3.8 | 8.4 | 2.25 ± 0.42 |
| mattcl-py | input-kcen | 31.9 ± 1.0 | 30.5 | 35.2 | 14.73 ± 2.28 |
| mattcl-py | input-mattcl | 32.0 ± 1.1 | 30.4 | 38.7 | 14.77 ± 2.30 |
| mattcl-py | input-lanjian | 32.0 ± 0.8 | 30.5 | 34.4 | 14.77 ± 2.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|