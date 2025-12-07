# Day 2 benchmarks

[link to problem](https://adventofcode.com/2025/day/2)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 2)

- [kcen](https://github.com/kcen/aoc2025) (nim)
- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2025-py) (python)
- [whyando](https://github.com/whyando/aoc-2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| whyando | input-mattcl | 406.3 ± 180.7 | 0.0 | 995.0 | 1.00 |
| whyando | input-lanjian | 450.7 ± 156.8 | 0.0 | 929.8 | 1.11 ± 0.63 |
| whyando | input-whyando | 459.9 ± 171.7 | 0.0 | 1028.4 | 1.13 ± 0.66 |
| mattcl | input-whyando | 618.0 ± 181.9 | 0.0 | 1300.5 | 1.52 ± 0.81 |
| mattcl | input-mattcl | 683.5 ± 138.0 | 159.5 | 1118.6 | 1.68 ± 0.82 |
| mattcl | input-lanjian | 687.4 ± 182.9 | 0.0 | 1195.0 | 1.69 ± 0.88 |
| kcen | input-whyando | 814.9 ± 150.9 | 89.3 | 1344.2 | 2.01 ± 0.97 |
| kcen | input-lanjian | 838.0 ± 171.7 | 0.0 | 1575.7 | 2.06 ± 1.01 |
| kcen | input-mattcl | 841.6 ± 157.6 | 0.0 | 1271.3 | 2.07 ± 1.00 |
| lanjian | input-whyando | 850.6 ± 175.0 | 62.8 | 1354.6 | 2.09 ± 1.03 |
| lanjian | input-lanjian | 899.2 ± 150.2 | 431.8 | 1507.6 | 2.21 ± 1.05 |
| lanjian | input-mattcl | 902.1 ± 158.2 | 0.0 | 1530.8 | 2.22 ± 1.06 |
| mattcl-py | input-whyando | 20560.2 ± 762.3 | 19079.8 | 23423.6 | 50.60 ± 22.59 |
| mattcl-py | input-mattcl | 20739.7 ± 640.8 | 19548.4 | 24119.2 | 51.05 ± 22.76 |
| mattcl-py | input-lanjian | 20755.2 ± 534.7 | 19767.2 | 24000.4 | 51.08 ± 22.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|