# Gas Optimizations in Solidity

## Gas Saving Patterns

### General Gas Saving Patterns

- [Proper Data Types](https://github.com/KadenZipfel/gas-optimizations/blob/main/gas-saving-patterns/general-gas-saving-patterns/proper-data-types.md)
- [Explicit Function Visibility](https://github.com/KadenZipfel/gas-optimizations/blob/main/gas-saving-patterns/general-gas-saving-patterns/explicit-function-visibility.md)
- [Immutable State Variables](https://github.com/KadenZipfel/gas-optimizations/blob/main/gas-saving-patterns/general-gas-saving-patterns/immutable-state-variables.md)
- [Short Revert Strings](https://github.com/KadenZipfel/gas-optimizations/blob/main/gas-saving-patterns/general-gas-saving-patterns/short-revert-strings.md)
- [Unchecked Arithmetic](https://github.com/KadenZipfel/gas-optimizations/blob/main/gas-saving-patterns/general-gas-saving-patterns/unchecked-arithmetic.md)
- [Optimal Comparison Operator](https://github.com/KadenZipfel/gas-optimizations/blob/main/gas-saving-patterns/general-gas-saving-patterns/optimal-comparison-operator.md)
- [Payable Functions](https://github.com/KadenZipfel/gas-optimizations/blob/main/gas-saving-patterns/general-gas-saving-patterns/payable-functions.md)
- [Function Ordering](https://github.com/KadenZipfel/gas-optimizations/blob/main/gas-saving-patterns/general-gas-saving-patterns/function-ordering.md)

### Technical Gas Saving Patterns

- [Short Circuiting](https://github.com/KadenZipfel/gas-optimizations/blob/main/gas-saving-patterns/technical-gas-saving-patterns/short-circuiting.md)

## Gas Costly Patterns

- [Comparison with Unilateral Outcome in a Loop](https://github.com/KadenZipfel/gas-optimizations/blob/main/gas-costly-patterns/comparison-with-unilateral-outcome-in-a-loop.md)
- [Constant Outcome of a Loop](https://github.com/KadenZipfel/gas-optimizations/blob/main/gas-costly-patterns/constant-outcome-of-a-loop.md)
- [Dead Code](https://github.com/KadenZipfel/gas-optimizations/blob/main/gas-costly-patterns/dead-code.md)
- [Expensive Operations in a Loop](https://github.com/KadenZipfel/gas-optimizations/blob/main/gas-costly-patterns/expensive-operations-in-a-loop.md)
- [Loop Fusion](https://github.com/KadenZipfel/gas-optimizations/blob/main/gas-costly-patterns/loop-fusion.md)
- [Opaque Predicate](https://github.com/KadenZipfel/gas-optimizations/blob/main/gas-costly-patterns/opaque-predicate.md)
- [Repeated Computations in a Loop](https://github.com/KadenZipfel/gas-optimizations/blob/main/gas-costly-patterns/repeated-computations-in-a-loop.md)
- [Storage Variable as Loop Length](https://github.com/KadenZipfel/gas-optimizations/blob/main/gas-costly-patterns/storage-variable-as-loop-length.md)
- [Unnecessary Libraries](https://github.com/KadenZipfel/gas-optimizations/blob/main/gas-costly-patterns/unnecessary-libraries.md)

## Sources/References

- https://medium.com/coinmonks/optimizing-your-solidity-contracts-gas-usage-9d65334db6c7
- https://ethereum.stackexchange.com/questions/28813/how-to-write-an-optimized-gas-cost-smart-contract
- https://arxiv.org/pdf/1703.03994.pdf
- https://ethereum.stackexchange.com/questions/3067/why-does-uint8-cost-more-gas-than-uint256
- https://www.youtube.com/watch?v=qwBkeJ84d2g&feature=youtu.be&t=68
- https://ethereum.stackexchange.com/questions/11556/use-string-type-or-bytes32
- https://gist.github.com/hrkrshnn/ee8fabd532058307229d65dcd5836ddc
- https://github.com/ZeroEkkusu/re-golf-course
