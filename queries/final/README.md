## 📐 Core DAX Architecture

To maximize data model performance and prevent calculation bottlenecks, all business intelligence aggregates are decoupled into isolated, relationship-aware expressions. 

The complete, production-ready syntax files can be reviewed directly in the project directory:

* 📂 [trip_hour.dax](./queries/final/trip_hour.dax) – Optimized extraction logic anchoring transit runs strictly to their initial chronological departure sequence.
* 📂 [trip_time_category.dax](./queries/final/trip_time_category.dax) – Dynamic conditional expression mapping network timelines into target Peak vs. Off-Peak operational bins.
