# Explained and Unexplained P&L

The target objective for a risk model is equivalency between the hypothetical full revaluation P&L (clean P&L) and hypothetical VaR P&L (model P&L). Clean P&L represents the full revaluation P&L driven by market factors (thus excludes the impact of new trades, date roll and fees/commissions). Model P&L represents the P&L computed using the market factors and valuation approach captured in the risk model (sensitivity based or full revaluation). Unexplained P&L represents the difference between Clean P&L and Model P&L.

When the unexplained P&L reaches above a minimum threshold of P&L (10%/$50K) and VaR (5%/$50K), a review needs to be initiated to understand the drivers. The Risk Measurement Performance Review Stream is tasked with reviewing and outlining any differences. The single valuation model framework between sensitivity based profit attribution and actual P&L will facilitate the identification of unexplained P&L.

A daily review of trade capture, market data, and model inputs will be required to confirm differences between these two P&L metrics. Confirmed differences between model P&L and clean P&L will often be the result of RNIV. These measures will be evaluated and tracked for each limit letter and legal entity roll-ups (such as BFC). Summary metrics tracking these thresholds along with drivers for the differences are to be presented to the Risk Measurement and Data Review Group by the Risk Measurement Completeness Review Stream. Material gaps identified as RNIV will need to be reviewed for inclusion of additional sensitivities to VaR or changes to risk factors.

To more effectively identify the root issue, the unexplained P&L can be split into the impact of a sensitivity approach and impact of risk factor selection using two additional P&L measures (risk based PAA P&L and full revaluation model P&L).

The impact of the sensitivity approach indicates a gap between full revaluation P&L and sensitivity based P&L. Reducing this difference requires the addition of new sensitivities to the model. A move to a full revaluation would completely remove this error in the model P&L. This difference will be tracked over time at the limit letter level and can be used to evaluate the potential improvement from changing the valuation approach in the model.

The impact of risk factor selection indicates the gap between a direct market instrument representation in valuation (see https://finpricing.com/lib/FiBond.html)  compared to mapping market data to risk factors and back to market instruments. As risk factors represent a selective choice of market instruments, differences attributed to risk factor selection will require a review of the risk factors and risk factor modelling assumptions. This difference will be tracked at the limit letter level.

Gaps identified by these two impacts should be investigated to understand drivers. The daily full revaluation backtest should be compared to the greek-based backtest to identify risks potentially not in VaR.

The unexplained component of PAA should also be separately reviewed to understand key drivers. To the extent that this is >10% of the total P&L, a PAA methodology review should be initiated to understand the drivers behind the unattributed P&L. The comparisons between backtest measures and PAA will be the responsibility of the Risk Measurement Completeness Review Stream. Investigations may lead to the identification of important new factors that should be included in PAA and/or VaR and recommended for implementation.


