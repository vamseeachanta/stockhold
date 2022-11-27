# StockHoldAnalysis

Stock analysis, logic and guidance for long-term holding of a stock market asset trading on US stock exchanges i.e. Nasdaq etc.

Helps manage a stock as a stand-alone portfolio

# Summary


# Usage

See 


See a [test file](https://github.com/vamseeachanta/stockhold/blob/master/src/stockhold/test/test_all_analysis_xom.py) to see how to perform analysis




## Technical Details

Mapping Dashboard UI to the financial analysis

| Analysis     | Code class | Code object   | Current Status | Description | 
|----------|------------|---------------|----------------|-----------|
| Insider <br> Insider Cost and Volumes | fc.fanalysis | insider_df_buy <br> insider_df_sell | done | - [x] ok?
| Insider <br> Relation | fc.fanalysis | insider_analysis_by_relation_df | done | - [x] ok?
| Insider <br> Timeline | fc.fanalysis | insider_analysis_by_timeline_df | done | - [x] ok?
| Insider <br> Relative Buy | fc.fanalysis | insider_df_buy | done | - [x] ok?
| Insider <br> Relative Sell | fc.fanalysis | insider_df_sell | done | - [x] ok?
| Institution <br> Institution | fc.fanalysis | df_institutional_holders | done | - [x] ok?
| Price <br> Price | fc.fanalysis | ta | done | - [x] ok?
| Technical <br> Volume | fc.fanalysis | ta | done | - [x] ok?
| Technical <br> cfm | fc.fanalysis | ta | done | - [x] ok?
| Technical <br> eom | fc.fanalysis | ta | done | - [x] ok?
| Technical <br> wt_price | fc.fanalysis | ta | done | - [x] ok?
| Technical <br> volatility | fc.fanalysis | ta | done | - [x] ok?
| Technical <br> volatility_hi_low | fc.fanalysis | ta | done | - [x] ok?
| Technical <br> ulcer | fc.fanalysis | ta | done | - [x] ok?
| Technical <br> strength | fc.fanalysis | ta | done | - [x] ok?
| Option <br> Call | fc.fanalysis | df_call_analysis | done | - [x] ok?
| Option <br> Put | fc.fanalysis | TBA | done | - [x] ok?

## Debt

Library TODO list to keep track of ideas.

**TODO**
- Add summary for all key analysis to help make faster decisions.
- Troubleshoot SEC data import. Advise users to put appropriate headers to avoid lock-out by SEC websites
- Add Logic Flowchart
- Improve to run visualization analysis only once per ticker. Currently running inefficiently. See example analysis output below
<code>
Analysis for ticker: RIG  ... COMPLETED
Analysis for ticker: RIG  ... COMPLETED
RIG
Analysis for ticker: RIG  ... COMPLETED
Analysis for ticker: RIG  ... COMPLETED
Analysis for ticker: RIG  ... COMPLETED
RIG</code>

## References

https://www.lynalden.com/covered-calls/

Getting into and out of stocks:
https://www.marketwatch.com/story/plan-now-when-to-get-back-into-stocks-11657920632
