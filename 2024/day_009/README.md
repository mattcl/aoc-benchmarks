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
| mattcl | input-lanjian | 2.2 ± 0.4 | 1.0 | 3.7 | 1.00 |
| mattcl | input-kcen | 2.3 ± 0.3 | 1.5 | 3.1 | 1.04 ± 0.24 |
| mattcl | input-mattcl | 2.4 ± 0.4 | 1.5 | 4.3 | 1.08 ± 0.26 |
| lanjian | input-mattcl | 2.6 ± 0.2 | 1.8 | 3.2 | 1.17 ± 0.24 |
| lanjian | input-kcen | 2.6 ± 0.3 | 1.7 | 4.5 | 1.18 ± 0.25 |
| lanjian | input-lanjian | 2.6 ± 0.2 | 1.7 | 4.8 | 1.18 ± 0.25 |
| kcen | input-mattcl | 3.9 ± 0.3 | 3.1 | 5.5 | 1.75 ± 0.35 |
| kcen | input-kcen | 4.0 ± 0.4 | 3.1 | 6.5 | 1.77 ± 0.37 |
| kcen | input-lanjian | 4.0 ± 0.4 | 3.0 | 6.6 | 1.78 ± 0.39 |
| mattcl-py | input-mattcl | 31.4 ± 0.7 | 30.1 | 33.9 | 14.06 ± 2.65 |
| mattcl-py | input-lanjian | 31.5 ± 0.9 | 30.4 | 34.5 | 14.11 ± 2.67 |
| mattcl-py | input-kcen | 31.6 ± 0.8 | 30.3 | 34.5 | 14.13 ± 2.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|