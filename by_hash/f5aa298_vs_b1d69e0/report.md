# Benchmark Report

## Job Properties

*Commit(s):* [TuringLang/Turing.jl@f5aa2986551f66ce7c57f282f5260031e375df01](https://github.com/TuringLang/Turing.jl/commit/f5aa2986551f66ce7c57f282f5260031e375df01) vs [TuringLang/Turing.jl@b1d69e0db225542c0370b6b8f171bfae33b82048](https://github.com/TuringLang/Turing.jl/commit/b1d69e0db225542c0370b6b8f171bfae33b82048)

*Triggered By:* [link](https://github.com/TuringLang/Turing.jl/pull/1146#issuecomment-595004588)

*Tag Predicate:* `ALL`

## Results

*Note: If Chrome is your browser, I strongly recommend installing the [Wide GitHub](https://chrome.google.com/webstore/detail/wide-github/kaalofacklcidaampbokdplbklpeldpj?hl=en)
extension, which makes the result table easier to read.*

Below is a table of this job's results, obtained by running the benchmarks found in
[JuliaCI/BaseBenchmarks.jl](https://github.com/JuliaCI/BaseBenchmarks.jl). The values
listed in the `ID` column have the structure `[parent_group, child_group, ..., key]`,
and can be used to index into the BaseBenchmarks suite to retrieve the corresponding
benchmarks.

The percentages accompanying time and memory values in the below table are noise tolerances. The "true"
time/memory value for a given benchmark is expected to fall within this percentage of the reported value.

A ratio greater than `1.0` denotes a possible regression (marked with :x:), while a ratio less
than `1.0` denotes a possible improvement (marked with :white_check_mark:). Only significant results - results
that indicate possible regressions or improvements - are shown below (thus, an empty table means that all
benchmark results remained invariant between builds).

| ID | time ratio | memory ratio |
|----|------------|--------------|
| `["gdemo", "hmc"]` | 1.06 (5%) :x: | 1.00 (1%)  |

## Benchmark Group List

Here's a list of all the benchmark groups executed by this job:

- `["dummy"]`
- `["gdemo"]`
- `["mnormal"]`

## Version Info

#### Primary Build

```
f5aa2986551f66ce7c57f282f5260031e375df01
```

#### Comparison Build

```
b1d69e0db225542c0370b6b8f171bfae33b82048
```
