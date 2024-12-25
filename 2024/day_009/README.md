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
| mattcl | input-mattcl | 2.1 ± 0.3 | 1.2 | 2.9 | 1.00 |
| mattcl | input-kcen | 2.2 ± 0.4 | 1.4 | 2.8 | 1.01 ± 0.23 |
| mattcl | input-lanjian | 2.2 ± 0.4 | 1.4 | 3.7 | 1.03 ± 0.24 |
| lanjian | input-mattcl | 2.4 ± 0.4 | 1.0 | 3.3 | 1.13 ± 0.26 |
| lanjian | input-lanjian | 2.5 ± 0.3 | 1.6 | 3.4 | 1.17 ± 0.23 |
| lanjian | input-kcen | 2.6 ± 0.3 | 1.5 | 4.5 | 1.20 ± 0.25 |
| kcen | input-mattcl | 3.8 ± 0.3 | 3.0 | 5.0 | 1.77 ± 0.33 |
| kcen | input-lanjian | 3.9 ± 0.5 | 3.0 | 7.6 | 1.83 ± 0.37 |
| kcen | input-kcen | 4.0 ± 0.5 | 3.2 | 7.4 | 1.87 ± 0.38 |
| mattcl-py | input-lanjian | 31.7 ± 0.8 | 30.4 | 34.7 | 14.85 ± 2.44 |
| mattcl-py | input-mattcl | 31.7 ± 1.0 | 30.4 | 34.8 | 14.87 ± 2.46 |
| mattcl-py | input-kcen | 31.8 ± 0.8 | 30.3 | 34.6 | 14.91 ± 2.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|