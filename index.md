<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
  <video
    src="ukhona/data-center.MP4#t=8"
    controls
    style="position: absolute; top: 0; center: 0; width: 65%; height: 100%;"
  ></video>
</div>

[Exactly](https://x.com/rohanpaul_ai/status/2009430600676200472?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Etweet) — that 1 GW figure tells you almost everything about the economics.

A $50 billion datacenter consuming roughly **1 gigawatt of continuous power** translates to:

* **8.76 terawatt-hours per year** (1 GW × 8,760 hours/year).
* At an industrial rate of, say, $0.05 / kWh, that’s **$438 million in annual electricity cost** — and that’s before cooling, redundancy, or power conditioning.

Now, why this matters for **profit margins**:

1. **[Energy is the limiting reagent](https://ukb-dt.github.io/journaling-02/)** in AI scaling. Compute cost scales roughly linearly with energy use (each watt drives a GPU, each GPU a parameter space). Once a model saturates its performance-per-watt curve, margins depend on power price and availability.

2. **[Capex amortization vs. opex squeeze.](https://ukb-dt.github.io/journaling-04/)** The $50 B upfront is mostly capital (chips, real estate, cooling, substations), while that 1 GW is opex that never goes away. If revenue per watt (say, from inference API calls or subscriptions) falls below energy cost per watt, margins collapse.

3. **The thermodynamic floor.** Every token generated or embedding computed corresponds to joules dissipated. So profit margins asymptotically approach the energy efficiency of computation — measured in joules per token or per FLOP.

4. **Integration advantage.** Whoever vertically integrates power (e.g., owns a nuclear SMR, or colocates with hydro/solar farms) can turn that 1 GW from a liability into a moat.

In short:

> A 1 GW data center is less a *tech* investment than an *energy arbitrage* play. Profit margins are bounded not by software efficiency, but by the cost of turning electrons into math.

Would you like a back-of-envelope estimate of how many model queries per day such a center would need to stay profitable? That’s a fun calculation.



