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
| mattcl | input-kcen | 2.2 ± 0.3 | 1.4 | 3.5 | 1.00 |
| mattcl | input-mattcl | 2.2 ± 0.4 | 1.3 | 4.8 | 1.02 ± 0.25 |
| mattcl | input-lanjian | 2.3 ± 0.3 | 1.4 | 3.6 | 1.04 ± 0.23 |
| lanjian | input-kcen | 2.6 ± 0.3 | 1.8 | 4.6 | 1.16 ± 0.23 |
| lanjian | input-mattcl | 2.6 ± 0.3 | 1.6 | 4.6 | 1.16 ± 0.22 |
| lanjian | input-lanjian | 2.6 ± 0.3 | 1.8 | 4.1 | 1.17 ± 0.22 |
| kcen | input-mattcl | 3.8 ± 0.3 | 3.2 | 5.3 | 1.74 ± 0.30 |
| kcen | input-lanjian | 3.9 ± 0.4 | 3.0 | 6.2 | 1.75 ± 0.33 |
| kcen | input-kcen | 4.2 ± 0.5 | 3.3 | 7.4 | 1.88 ± 0.38 |
| mattcl-py | input-mattcl | 31.5 ± 1.0 | 29.9 | 34.7 | 14.27 ± 2.30 |
| mattcl-py | input-lanjian | 31.6 ± 0.8 | 30.2 | 34.7 | 14.34 ± 2.29 |
| mattcl-py | input-kcen | 31.7 ± 0.9 | 30.6 | 35.1 | 14.37 ± 2.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|