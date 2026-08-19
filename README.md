# investment-toys
Personal repo for investment visualization toys

Currently there are two toys (in Finnish only, sorry):
- [stock-growth-simulation](https://esiivola.github.io/investment-toys/stock-growth-simulation.html): A tool for visualizing stock/investment return/volatility
- [investment-growth-visualization](https://esiivola.github.io/investment-toys/investment-growth-visualization.html): A tool for visualizing average returns for your (simple) investment strategy

## Running locally

The pages are static HTML, but `stock-growth-simulation.html` fetches `stock_data_processed.json`, which browsers block over `file://`. Serve the folder over HTTP instead:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000/stock-growth-simulation.html>.
