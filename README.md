# London Tube Network Resilience Analysis

This project models the **London Underground as a graph** and analyses how the network responds to different station-closure scenarios.

## Summary
- Builds **undirected graph representations** of:
  - The full London Tube network
  - A Central London subnetwork
- Data is downloaded from the **TfL Unified API**
- Uses **NetworkX** for network construction and analysis
- Compares two disruption scenarios:
  - Closure of the **top 5 stations by betweenness centrality**
  - Closure of **5 random stations**
- Evaluates network impact using **efficiency / shortest-path structure**
- Applies **Girvan–Newman community detection** to examine whether closed stations lie between communities

## Methods
- Graph construction with geographic coordinates
- Betweenness centrality (NetworkX)
- Random node removal (fixed random seed)
- **Girvan–Newman algorithm** for community detection
- Network visualisation before and after closures

## Main File
- `UDA_FinalProject_Dhileepan.ipynb` — full analysis, simulations, and plots

## Libraries
- `networkx`
- `requests`
- `numpy`
- `math`
- `random`
- `matplotlib`

## Runtime Information
- Code created and run on a laptop
- Total runtime is **less than two minutes**

## How to run
```bash
jupyter notebook UDA_FinalProject_Dhileepan.ipynb