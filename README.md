# benchtest

Requires nightly compiler for internal test crate.

    #![feature(test)]

    use benchtest::benchtest;
    
    // ...

    benchtest! {
        part_a_test: solve_a(INPUT) => 5434,
        part_b_test: solve_b(INPUT) => "agimdjvlhedpsyoqfzuknpjwt"
    }