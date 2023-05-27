# FinOps-Cheatsheet

## FinOps Lifecycle

```mermaid
mindmap
  root((phases))
    Inform
      Forecasting
      Realtime decision making
        Spotting outlying data
        Integrate to internal systems
        Shared cost allocation
        Make recommendations
        
      Visibility
      ::icon(fa fa-book)
        Consuming Teams
        Stakeholders 

    Optimise
      Identify
      Value for effort
      Evaluate discounts from provider
        RI
        Spot
        Discounts
    Operate
      Processes
      Automation
```


## FinOps Domains

https://www.finops.org/framework/domains/

```mermaid
mindmap
  root((phases))
    Understanding Usage and Cost
      Measure UNIT cost
      Anomalies
      Data Ingestion
      ::icon(fa fa-table)
      Data Analysis and Showback
      Shared Cost
      Forecasting
      ::icon(fa fa-chart-line)
      Cost allocation
      ::icon(fa fa-sitemap)

    Perf Tracking and Benchmarking
      Util & efficiency
      Measure UNIT cost
      Commitment based discounts
      Anomalies
      Forecasting
      Budget

    RealTime decision making
      Measuring UNIT cost
      Anomalies
      Decision structure (remit)
      Data Analysis and Showback
    
    Cloud RATE optimisation
      Commitment based discounts
      Data Analysis and Showback
    
    Cloud USAGE optimisation
      Automation
      Util & efficiency
      Onboarding 
        Process and guidance maturity
      Data Analysis and Showback

    Org Alignment
      Integration with other frameworks
      Culture
      Shared Cost
      Education and enablement
      Chargeback
      Finance and budgets
      

```

## Terms

Some real FinOpsy terms to be familiar with.

Term | Description
---- | -----------
Vacancy | Not using commitment based discounts (Reserved Instances) fully
Fully Loaded Costs |  Reflect the true cost, factoring in shared costs and mapped to the org
Blended rates | The effective rate, factoring in discounts etc
Unblended rates | The raw rates that could include more complex, time based pricing models
Showbacks  | Shows expenses to org department but keeps them in a central budget
Chargebacks | Sends expenses to org departnment
Cloud Unit Economics | Org specific KPI's to measure FinOps success against. Eg. Cost per item/user/gb
Rate Optimisation | Changing the price through discounts like Reserved Instances
Usage Optimisation | Rightsizing, turning unused resources off
Workload management | Only running resoruces when needed
