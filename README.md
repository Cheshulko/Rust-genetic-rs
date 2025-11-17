# Rust-Genetic

This project presents a prototype genetic algorithm for the Traveling Salesman Problem (TSP) implemented in Rust.

The diploma thesis proposes implementing a flexible, parameterized genetic algorithm to find near‑optimal solutions for the TSP, together with a tool to visualize the search process.

The developed algorithm can be adapted to investigate and solve other NP‑hard problems to a specified accuracy. Each genetic operation probability is parameterized and can be tuned conveniently for a particular problem.

I implemented step‑by‑step visualization for each population generation and visualization of the fitness function across generations. This makes it easy to visually monitor the evolution of the population and to select parameters for improved solution accuracy.

# To run

```
cargo run ./config0.csv ./cities0.csv > ./output0.csv
```

# To plot
```
python3 plot.py ./cities0.csv ./output0.csv
```

![](pict/Video.gif)

# License

MIT
