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
| mattcl | input-lanjian | 616.9 ± 144.4 | 0.0 | 1146.8 | 1.00 |
| mattcl | input-whyando | 618.2 ± 152.1 | 0.0 | 1043.6 | 1.00 ± 0.34 |
| mattcl | input-mattcl | 629.6 ± 200.5 | 0.0 | 1384.8 | 1.02 ± 0.40 |
| kcen | input-mattcl | 783.5 ± 120.9 | 241.1 | 1071.2 | 1.27 ± 0.36 |
| kcen | input-whyando | 799.9 ± 130.3 | 0.0 | 1212.7 | 1.30 ± 0.37 |
| whyando | input-whyando | 813.8 ± 205.6 | 238.9 | 1353.5 | 1.32 ± 0.45 |
| lanjian | input-whyando | 827.5 ± 152.2 | 346.9 | 1317.8 | 1.34 ± 0.40 |
| lanjian | input-lanjian | 856.1 ± 191.4 | 0.0 | 1529.2 | 1.39 ± 0.45 |
| kcen | input-lanjian | 865.1 ± 174.5 | 303.9 | 1536.8 | 1.40 ± 0.43 |
| whyando | input-mattcl | 888.3 ± 161.3 | 133.6 | 1462.6 | 1.44 ± 0.43 |
| lanjian | input-mattcl | 894.7 ± 178.6 | 249.8 | 1407.2 | 1.45 ± 0.45 |
| whyando | input-lanjian | 911.7 ± 158.5 | 24.9 | 1472.1 | 1.48 ± 0.43 |
| mattcl-py | input-whyando | 20355.4 ± 709.5 | 19221.8 | 25863.6 | 33.00 ± 7.81 |
| mattcl-py | input-lanjian | 20668.1 ± 617.7 | 19586.1 | 23504.9 | 33.51 ± 7.91 |
| mattcl-py | input-mattcl | 20701.5 ± 743.7 | 19663.1 | 24246.9 | 33.56 ± 7.95 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>19605500130</pre>|<pre>36862281418</pre>|
|input-mattcl|<pre>23701357374</pre>|<pre>34284458938</pre>|
|input-whyando|<pre>24043483400</pre>|<pre>38262920235</pre>|