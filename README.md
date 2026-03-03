# Orange Line Ridership History

This project uses a K-mean clustering to examine shifts in pre and post COVID(2019) CTA Orange Line Ridership as well as has a short exploratory data analysis

I used (2) data sets from the Chicago Portal: 
 * (A) CTA - Ridership - 'L' Station Entries - Monthly Day-Type Averages & Totals
 * (B) CTA - System Information - List of 'L' Stops

I used map_id from set (B) and mapped it to station_id in set (A) to identify unique Orange Line Stations.


# Summary:
COVID shifted the riderhsip patterns for Orange Line riders. When looking at 2020-2025 ridership data, we can see that ridership has drastiavlly delcined since 2018. Additionally, we see some stations with a considerable drop in their porpotional weekday rides:

Clark/Lake was mainly driven by a drop in weekday rides(largest shift)
* 35th/Archer was mainly driven by a drop in weekday rides
* Washington/Wells mainly driven by a drop in weekday rides
* Midway Airport mainly driven by a drop in weekday rides
* LaSalle/Van Buren mainly driven by a drop in weekday rides
* Pulaski-Orange mainly driven by a drop in weekday rides

When comparing k-mean clusters for pre-COVID years (2008-2018) with post-COVID years (2020-2025) we see a shift in ridership behavior at the station level. Post-COVID, we see stations State/Lake and Washiston/Wabash shift up to a cluster with

* extremely high total ridership
* Strong weekday AND strong weekend traffic
* Likely downtown, transfer, airport, entertainment centers
* This indicates a need for highest staffing, security, maintenance

We also see that stations Pulaski, Quincy/Wells, and Washinton/Wells shift up to a cluster(Commuter-Dominant Stations) with

* High weekday traffic
* Moderate weekend traffic
* business district commute flow
  
This indicates a need for weekday peak service

## Insight:
Yes, COVID affected public transit patterns, but not all communities were impacted equally. With this analysis, we can recalibrate service, staffing, and resource allocation to match the new ridership reality. Key takeaways include:

High-volume, mixed-use stations (e.g., State/Lake,  Washington/Wabash) now experience strong weekday and weekend traffic. These stations likely serve downtown hubs, transfer points, airport connections, or entertainment areas. They require increased staffing, security, and maintenance to handle the consistently high demand.

Commuter-dominant stations (e.g., Pulaski, Quincy/Wells,  Washington/Wells) still see strong weekday traffic but moderate weekend activity. These stations primarily support business district commuting, highlighting the need for weekday peak service optimization.

Neighborhood or low-traffic stations experienced relatively smaller changes, suggesting that service levels can be maintained or adjusted moderately based on evolving usage patterns. *Its important to note that the Pulaski station is the only neighborhood station that saw a dramatic shift in ridership behavior patterns. This could indicate a shift in nearby housing, population shift , etc.*

By combining ridership trends with cluster analysis, transit planners can target resources more efficiently, adapt schedules to shifting demand, and ensure that both commuter and high-traffic hub stations are adequately supported post-COVID. This approach allows the transit system to respond dynamically to changing travel behaviors while maintaining safety and service quality.
